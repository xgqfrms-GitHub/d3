# D3: 数据驱动 文档 

<a href="https://d3js.org"><img src="https://d3js.org/logo.svg" align="left" hspace="10" vspace="6"></a>

**D3** (or **D3.js**) 是一个基于Web标准的JavaScript库，用于数据可视化。D3帮助你使用SVG，Canvas和HTML将数据带到生活中。D3以数据驱动的方式操作DOM，结合了功能强大的可视化和互动技术，让你使用现代浏览器全部功能，自由的为你的数据设计合适的可视化界面。

## 资源

* [API 参考](https://github.com/d3/d3/blob/master/API.md)
* [发行 说明](https://github.com/d3/d3/releases)
* [画廊](https://github.com/d3/d3/wiki/Gallery)
* [范例](http://bl.ocks.org/mbostock)
* [Wiki](https://github.com/d3/d3/wiki)

## 安装

If you use npm, `npm install d3`. Otherwise, download the [latest release](https://github.com/d3/d3/releases/latest). The released bundle supports anonymous AMD, CommonJS, and vanilla environments. You can load directly from [d3js.org](https://d3js.org), [CDNJS](https://cdnjs.com/libraries/d3), or [unpkg](https://unpkg.com/d3/). For example:

```html
<script src="https://d3js.org/d3.v4.js"></script>
```

For the minified version:

```html
<script src="https://d3js.org/d3.v4.min.js"></script>
```

You can also use the standalone D3 microlibraries. For example, [d3-selection](https://github.com/d3/d3-selection):

```html
<script src="https://d3js.org/d3-selection.v1.js"></script>
```

D3 is written using [ES2015 modules](http://www.2ality.com/2014/09/es6-modules-final.html). Create a [custom bundle using Rollup](http://bl.ocks.org/mbostock/bb09af4c39c79cffcde4), Webpack, or your preferred bundler. To import D3 into an ES2015 application, either import specific symbols from specific D3 modules:

```js
import {scaleLinear} from "d3-scale";
```

Or import everything into a namespace (here, `d3`):

```js
import * as d3 from "d3";
```
