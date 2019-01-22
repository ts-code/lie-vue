# LieVue - Admin  Bootstrap 4
## Installation

Several options are available:

### Clone repo

``` bash
$ git clone https://github.com/ts-code/lie-vue.git
```

### NPM

``` bash
$ npm install ts-code/lievue --save
```


## Usage

### CSS

Copy-paste the stylesheet `<link>` into your `<head>` before all other stylesheets to load our CSS.

``` html
<link rel="stylesheet" href="node_modules/ts-code/lievue/dist/css/lievue.min.css">
```

### JS

Many of our components require the use of JavaScript to function. Specifically, they require [jQuery](https://jquery.com), [Popper.js](https://popper.js.org/), [Bootstrap](https://getbootstrap.com) and our own JavaScript plugins. Place the following `<script>`s near the end of your pages, right before the closing `</body>` tag, to enable them. jQuery must come first, then Popper.js, then Bootstrap, and then our JavaScript plugins.

``` html
<script src="node_modules/jquery/dist/jquery.min.js"></script>
<script src="node_modules/popper.js/dist/umd/popper.min.js"></script>
<script src="node_modules/bootstrap/dist/js/bootstrap.min.js"></script>
<script src="node_modules/ts-code/lievue/dist/js/lievue.min.js"></script>
```

## What's included

Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:

```
lievue/
├── build/
├── dist/
├── js/
└── scss/
```
