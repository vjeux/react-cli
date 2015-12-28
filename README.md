# react-cli

This repo is an exploration for making the tooling for React that provides the best developer experience.


## Getting started should be dead simple

Something like `npm install -g react-cli` then `react init cool-project`.

## Gradual integration

The initial setup should be super slim, but then you can add more to it. When you start to want to test your app, you can do `react add test`, if you want to use flow then `react add flow`, wanna add crash reporting then `react add sentry`...

Once you added a module (for example `react add test`) to your setup, it is registered as an executable on `react`. So you can do `react test` or `react test --add MyModule.js`...

## More than a boilerplate generator

- `react add redux` should not only add redux to your project but also add the redux dev tools to Chrome.
- `react serve` should open the url in Chrome and open the project in Atom.
- `react add github` should create the license file, `git init` and create an initial commit, create the github repo and push it.

## Extensibility

