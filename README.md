# yarnx

![Build and Deploy](https://github.com/terminal-junkies/yarnx/workflows/Build%20and%20Deploy/badge.svg)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)
[![npm version](http://img.shields.io/npm/v/@terminal-junkies/yarnx.svg?style=flat)](https://npmjs.org/package/@terminal-junkies/yarnx "View this project on npm")

An advanced CLI interface for [yarn](https://classic.yarnpkg.com/en/)

Features:
- Search packages from the terminal
- Run your project tasks from
- Install a selected package with one keystroke
- Run other npm tasks within your project
- Mnemonic key-bindings for installing packages


## Install

```
npm install --global @terminal-junkies/yarnx
```

## Usage

```
yarnx
```

## Screenshots

[![asciicast](https://asciinema.org/a/7ajz46JAVDVR9nV5ZMwhLLzAT.svg)](https://asciinema.org/a/7ajz46JAVDVR9nV5ZMwhLLzAT)

### Home
![home page](screenshots/home.png)

### Package
![package info](screenshots/package-info.png)

### Package
![tasks](screenshots/tasks.png)

### Search
![search page](screenshots/search.png)

### Package
![package page](screenshots/package-page.png)

## FAQS

### How do I quit this thing?
You can press `q` to quit the program at any time.

### How do I scroll the package readme?
You can use `up` and `down` arrow keys to scroll. And you can also make use of vim navigation keys like `j,k,gg,G` to scroll.

### How can I see the keyboard shortcuts for navigating?
The keyboard shortcuts will be displayed at the bottom of the screen for each page.

### How do I close the project task terminal after the task is completed?
Press `Esc` to close the terminal window for project tasks.

### Does it support vi/vim navigation keys in the lists?
Yes. You can use j,k,gg,G,l and /
