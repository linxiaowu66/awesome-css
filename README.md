## What is this?

some useful css functions which sass syntax and less syntax. You can download and import to your project, each function has corresponding example. check it in example folder.

# Changelog

* 2024.5.7：适配最新的Sass版本：1.77.0 与最新的less版本：4.2.0

## How to Run

1. install sass and less globally

    `npm install -g sass`

    `npm install -g less`

2. cd example

    `cd example`

3. Run the sass or less compiler

    `sass --watch sass.scss:sass.css `
    或：
    `lessc  less.less less.css`

## Features

|                 feature                | moduleName   | scss | less |
|:--------------------------------------:|--------------|------|------|
| vertical & horizontal & both center    | _center      | ✅    | ✅    |
| clear fix                              | _clearfix    | ✅    | ✅    |
| ellipse text                           | _ellipsis    | ✅    | ✅    |
| gradient background                    | _gradient    | ✅    | ✅    |
| hidden scroll bar(only webkit engine)  | _noScroll    | ✅    | ✅    |
| draw the 0.5px or full border with 1px | _onePxBorder | ✅    | ✅    |
| px unit transform to rem unit          | _px2rem      | ✅    | ✅    |
| draw triangle for all directions       | _triangle    | ✅    | ✅    |
| draw gradient border             | _gradientBorder    | ✅    | ✅    |

## Note

Almost syntax for scss and less are the same, but someone maybe is different, eg. `px2rem`.

In the scss, you can transfer singer px attribute to rem as: `margin: px2rem(10px);`,

Buy with less syntax, it will change to this: `margin: 10/@toRem;`
