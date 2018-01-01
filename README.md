<img src="https://user-images.githubusercontent.com/659829/34358025-e49c0b0e-ea00-11e7-990b-bc189723168d.png" alt="gridss logo" width="300">

[![npm](https://img.shields.io/npm/v/gridss.svg?style=flat-square)](https://www.npmjs.com/package/gridss)

### Description

gridss provides a 12-column grid applied using object oriented css.

**[Demo →](https://codepen.io/briangonzalez/pen/jYyOOw?editors=1100)**

### Installation & Usage

```
npm install --save gridss
```

```html
<link rel="stylesheet" href="https://unpkg.com/gridss/grid.min.css">
```

### Docs

The source code is quite explanatory, but here are the general classes you can apply:

```
.gridss
.col-{1..12}
.col-xs-{1...12}
.col-s-{1...12}
.col-m-{1...12}
.col-l-{1...12}
.col-xl-{1...12}
```

For example:

```html
<div class="gridss">
  <div class="col-xs-12 col-s-10 col-m-8 col-l-6 col-xl-4 col-1">
    12 columns under 400px
    10 columns under 780px
    8 columns under 1024px
    6 columns under 1280px
    4 columns under 1400px
    1 column
  </div>
</div>
```

## License

MIT
