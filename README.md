# Electron Demo

Simple [Electron](https://github.com/atom/electron) (formerly Atom Shell) boilerplate app 
since if you ask me the official [Electron-Starter](https://github.com/atom/electron-starter) 
seems overly-complicated.

[![Circle CI](https://circleci.com/gh/thom-nic/electron-demo.svg?style=svg)](https://circleci.com/gh/thom-nic/electron-demo) [![Dependencies](https://david-dm.org/thom-nic/electron-demo.svg)](https://david-dm.org/thom-nic/electron-demo) [![DevDependency Status](https://david-dm.org/thom-nic/electron-demo/dev-status.svg)](https://david-dm.org/thom-nic/electron-demo#info=devDependencies)

![electron-demo mov](https://cloud.githubusercontent.com/assets/95562/7319912/2004f03a-ea67-11e4-852f-f558af75b078.gif)

## Features

* ES6 support (via babel) + eslint
* Less CSS
* Mithril

**Note:** There's technically no need for browserify (unless you want to use it
for something like JSX/ MSX transforms) since Electron already provides the 
full node.js environment in the browser.

## Getting Started

```
nvm install
npm install
npm start
```
Changes will be rebuilt automatically, but you will still have to `Ctrl-R`
in the app window to reload changes.

## Reference

* [Electron Quick Start](https://github.com/atom/electron/blob/master/docs/tutorial/quick-start.md)
* [Electron docs](https://github.com/atom/electron/tree/master/docs)
