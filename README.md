# SASS WATCHER POC

📡 Simple SASS watcher without anything else than your terminal 💻

This is a simple POC to show how to get a custom SASS watcher running in your web project.

## Requirements

- Node JS (v10+)
- Yarn

## Installation

* You don't need to install anything in your project if you already have installed SASS globally on your computer.
Like `yarn global add sass`.<br />
If not, you still can do it 😁!

* If ever you don't want to install SASS globally, you can just install this project's dependencies doing `yarn install`

This will install SASS in the project's `node_modules` folder.

## Launch watcher

**At root of project, launch:**

**```yarn watch```**

Note that compiled _CSS won't be compressed_ with this command.

## Production build

The built version can be compiled simply doing **`yarn build`**.
The compiled CSS file will be compressed.

---

## Licence

DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 
Version 2, December 2004 

Copyright (C) 2004 Sam Hocevar <sam@hocevar.net> 

Everyone is permitted to copy and distribute verbatim or modified 
copies of this license document, and changing it is allowed as long 
as the name is changed. 

DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 
TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION 

0. You just DO WHAT THE FUCK YOU WANT TO.