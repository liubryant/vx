<p align="center">
  <img src="./assets/Screen Shot 2017-05-05 at 6.55.56 AM.png" />
</p>

<p align="center">
  <img src="https://img.shields.io/npm/v/@vx/demo.svg?style=flat-square" />
  <img src="https://img.shields.io/npm/dm/@vx/demo.svg?style=flat-square" />
</p>

### vx

vx is collection of reusable low-level visualization components. vx combines the power of d3 to generate your visualization with the benefits of react for updating the DOM.

### [View Docs](https://vx-demo.now.sh)

## Motivation

**Goal**

The goal is to create a library of components you can use to make both your own reusable chart library or your slick custom one-off chart. vx is largely unopinionated and is meant to be build on top of. Keep your bundle sizes down and use only the packages you need.

**How?**

Under the hood, vx is using d3 for the calculations and math. If you're creating your own awesome chart library on top of vx, it's easy to create a component api that hides d3 entirely. Meaning your team could create charts as easily as using reusable react components.

**But why?**

Mixing two mental models for updating the DOM is never a good time. Copy and pasting d3 code into `componentDidMount()` is just that. This collection of components lets you easily build your own reusable visualization charts or library without having to learn d3. No more selections or `enter()`/`exit()`/`update()`.

## Status

`Super beta` Hold off on using this in production until I shake out some of the bigger API problems (post v1.0.0+).

If you're a curious coder, feel free to install and play around with the packages. I recommend using `--save-exact` when you `npm install`.

## Roadmap

Lots coming soon, check out the [roadmap](./ROADMAP.md).

## FAQ

1. What does `vx` stand for?

    > vx stands for visualization components.

1. Do you plan on supporting animation/transitions?

    > yup!

1. Do I have to use every package to make a chart?

    > nope! pick and choose the packages you need.

1. Can I use this to create my own library of charts for my team?

    > Please do.

1. I like using d3.

    > Me too.

:v:

[MIT](./LICENSE) &bull; [@hshoff](https://twitter.com/hshoff)
