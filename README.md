# Learn React Source Code

* [Day1 - Guidance](blog/guidance.md)
* [Day2 - Mounting](blog/mounting.md)
* [Day3 - Mounting - Contd](blog/mounting-contd.md)
* [Day4 - Updating - The Process Flow](blog/update.md)
* [Day5 - Updating - Diff](blog/update-contd.md)
* [Day6 - Updating - Real DOM Update](blog/update-dom.md)

## What You'll Learn

## What Dilithium Hasn't Covered

As it is a simplest implementation of React, it leaves out a lot of features of it. Below are something that it hasn't covered (This is originally shown in the React Rally talk by Paul in 2016):

* `defaultProps`
* `propTypes`
* `keys`
* `refs`
* batching
* events
* createClass
* warnings
* browser
* optimizations
* rendering null
* DOM updates
* SVG
* life cycle hooks
* error boundaries
* perf tooling and optimizing
* `PureComponents`
* functional components

## Run the Demo

```sh
> cd ./demo
> npm install
> npm run watch
```

Open the `index.html` manually.

## Disclaimers

1. Most code of Dilithium you've seen in this repo is originally written by [@zpao](https://github.com/zpao), at [building-react-from-scratch](https://github.com/zpao/building-react-from-scratch), but it's also slightly changed here. I'll keep digging some of the listed features and adding blog and source code on top of the current codebase.

2. The diffing algorithm used in the Dilithium is the stack reconcilliation, not the new fiber architecture.

3. The code snippets in the blogs are sometimes somewhat different from that in the codebase. This is for better readablity and a more smooth learning curve.

## Liscense

MIT[@Chang](github.com/cyan33)
