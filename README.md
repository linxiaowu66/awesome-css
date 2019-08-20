## What is this?

some useful css functions which sass syntax and less syntax. You can download and import to your project, each function has corresponding example. check it in example folder.

## How to Run

1. install sass and less globally

    `npm install -g sass`

    `npm install -g less`

2. cd example

    `cd example`

3. Run the sass or less compiler

    `sass --watch sass.scss:sass.css `



## Note

Almost syntax for scss and less are the same, but someone maybe is different, eg. `px2rem`.

In the scss, you can transfer singer px attribute to rem as: `margin: px2rem(10px);`,

Buy with less syntax, it will change to this: `margin: 10/@toRem;`
