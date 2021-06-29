# Uglify for browser

## CDN

```js
<script src="https://cdn.jsdelivr.net/gh/shiva-sandupatla/Uglify-for-browser@latest/index.min.js"></script>

```

## Usage


```js
var code = "function add(first, second) { return first + second;};";
var result = UglifyJS.minify(code);
console.log(result.error);
console.log(result.code);

```
