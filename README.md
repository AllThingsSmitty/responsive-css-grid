# Responsive CSS Grid

[![NPM version](https://img.shields.io/npm/v/responsive-css-grid.svg?)](https://www.npmjs.com/package/responsive-css-grid)

A super-lightweight, responsive, 8-column grid based on `box-sizing`.


## Getting Started

You may install this plugin with this command:

```shell
npm install responsive-css-grid --save-dev
```

**Issues with the output should be reported on the `responsive-css-grid` [issue tracker](https://github.com/allthingssmitty/responsive-css-grid/issues).**


## Usage

```html
<div class="container">

  <div class="row clearfix">
    <div class="col-2-3"> <!-- column is 2/3 the total width -->
      Your content
    </div>
    <div class="col-1-3"> <!-- column is 1/3 the total width -->
      Your content
    </div>
  </div>

  <div class="row clearfix">
    <div class="col-1-4"> <!-- column is 1/4 the total width -->
      Your content
    </div>
    <div class="col-1-2"> <!-- column is 1/2 the total width -->
      Your content
    </div>
    <div class="col-1-4"> <!-- column is 1/4 the total width -->
      Your content
    </div>
  </div>

</div>
```


## Live Example

[Responsive CSS grid](http://codepen.io/AllThingsSmitty/full/YqEbPB).


## Browser support

The responsive CSS grid works in the latest versions of:

* Chrome
* Firefox
* Opera
* Safari
* Edge
* Internet Explorer
* iOS Safari
* Chrome for Android

The above list is non-exhaustive. This grid works perfectly with any browser that supports `box-sizing`, including IE8+.


## License

[The MIT License (MIT)](https://github.com/AllThingsSmitty/responsive-css-grid/blob/master/LICENSE)