<img src="https://user-images.githubusercontent.com/659829/34358025-e49c0b0e-ea00-11e7-990b-bc189723168d.png" alt="gridss logo" width="300">

[![npm](https://img.shields.io/npm/v/gridss.svg?style=flat-square)](https://www.npmjs.com/package/gridss)

### Description

gridss provides a mobile-first 12-column grid applied using object oriented css.

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

**Container**

```
.gridss
```

**Span Columns**
```
.col-{1..12}
.col-s-{1...12}
.col-m-{1...12}
.col-l-{1...12}
.col-xl-{1...12}
```

**Start-End Columns**

```
.col-s-{1...12}-{1-12}
.col-m-{1...12}-{1-12}
.col-l-{1...12}-{1-12}
.col-xl-{1...12}-{1-12}
```

For example:

```html
<div class="gridss">
  <div class="col-12 col-s-10 col-m-8 col-l-6 col-xl-4">
    12 columns mobile
    10 columns x-small and above
    8 columns medium and above
    6 columns large and above
    4 columns x-large and above
  </div>
</div>
```

```html
<div class="gridss">
  <div class="col-1-8"></div>
  <div class="col-8-13"></div>
</div>
```

### What do you mean by mobile first?

It means that the sized-based grid classes function on _that size and larger._

**mobile first (like gridss)**: `col-l-6` applied to widths at or above "large"
**not mobile first**: `col-l-6` applied to width at or below "large"

## License

MIT
