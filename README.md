# Setting up Yarn Workspaces with Webpack

I'm trying to set up yarn workspaces with Webpack, but I can't seem to get webpack to recognize `babel-loader`.

I originally set up this repo using guidance from [this article](https://medium.com/trabe/monorepo-setup-with-lerna-and-yarn-workspaces-5d747d7c0e91). It mentions using a tools package instead of polluting the main workspace. I am trying to accomplish that with webpack, but can't seem to get the `babel-loader` to work.

## To Recreate

```
$ yarn install
$ yarn --cwd packages/client build
```
