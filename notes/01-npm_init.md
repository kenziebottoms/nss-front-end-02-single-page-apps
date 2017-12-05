# Using Grunt

## Setup

### Initialize an `npm` project for use with Grunt

In the root of your project folder:

```shell
> npm init -y
```

`-y` say yes to every question `npm init` would otherwise ask you.

### Install necessary `npm` modules

```shell
> npm install grunt grunt-contrib-jshint grunt-contrib-sass grunt-contrib-watch matchdep grunt-browserify
```

### Configure `Gruntfile.jmains`

If using JSLint, SASS, and Browserify, clone lone sample [`Gruntfile.js`](https://gist.github.com/kenziebottoms/dc4a300447652b63a29bc489670992e8).

### Preempt your JS

If you've already written any Javascript, add this to the beginning of every file.

```Javascript
"use strict";
```

### Wing it

```shell
> grunt
```

## Troubleshooting