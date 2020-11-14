# SASS WATCHER POC

📡 Simple SASS watcher without anything else than your terminal 💻

This is a simple POC to show how to get a custom SASS watcher running in your web project.

## Requirements

- Node JS (v10+)
- Yarn

## Installation

You don't need to install anything in your project if you already have installed SASS globally on your computer.
Like `yarn global add sass`

If not, you still can do it 😁!

If ever you don't want to install sass globally, you can just install this project's dependancies doing `yarn install`

This will install SASS in the project's `node_modules` folder.

## Launch watcher

At root of project, launch

```yarn watch```

Note that compiled CSS won't be compressed with this command.

## Production build

The built version can be compiled simply doing `yarn build`.
The compiled CSS file will be compressed.
