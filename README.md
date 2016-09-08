Basic static site build template
=============================

A starter project with a fully pimped out Gulp build and inuit css framework

## System Preparation

To use this starter project, you'll need the following things installed on your machine.

1. [Jekyll](http://jekyllrb.com/) - `$ gem install jekyll`
2. [NodeJS](http://nodejs.org) - use the installer.
3. [GulpJS](https://github.com/gulpjs/gulp) - `$ npm install -g gulp` (mac users may need sudo)

## Local Installation

1. Clone this repo, or download it into a directory of your choice.
2. Inside the directory, run `npm install`.

## Usage

**development mode**

This will give you file watching, browser synchronisation, auto-rebuild, CSS injecting etc etc.

```shell
$ gulp
```

BrowserSync is not set to open a new window everytime you 'build' (trust me, it gets annoying). So you'll need to navigate to the local address it gives you after running `gulp` (usually something like 'localhost:3000'). After that, if you quit and re-run gulp, you will need to reload the page manually just for the first time. If you prefer opening a new tab every time, simply change `open: false` to `open: true` in the browsersync settings in gulpfile.js.
