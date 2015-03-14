# text-modules

A collection of modules for processing, manipulating, and rendering text and fonts in Node and the browser. Please open an issue or submit a PR for suggestions/improvements.

# Font Processing

- [opentype.js](https://www.npmjs.com/package/opentype.js)
- [freetype2](https://www.npmjs.com/package/freetype2)

# Path / Vector Utils

- [vectorize-text](https://www.npmjs.com/package/vectorize-text)
- [earcut](https://www.npmjs.com/package/earcut) small and fast triangulation module
- [triangulate-polyline](https://www.npmjs.com/package/triangulate-polyline) uses poly2tri
- [triangulate-contours](https://www.npmjs.com/package/triangulate-polyline) uses Tess2
- [adaptive-bezier-curve](https://www.npmjs.com/package/adaptive-bezier-curve)
- [simplify-path](https://www.npmjs.com/package/simplify-path)
- [chaikin-smooth](https://www.npmjs.com/package/chaikin-smooth)
- [robust-orientation](https://www.npmjs.com/package/robust-orientation) and [is-clockwise](https://www.npmjs.com/package/is-clockwise)

# Bitmap Text

### testing

- [bmfont-lato](https://www.npmjs.com/package/bmfont-lato) Lato packed as a BMFont for testing

### CLI tools

- [image-sdf](https://www.npmjs.com/package/image-sdf) get an image's Signed Distance Field
- [parse-bmfont](https://www.npmjs.com/package/parse-bmfont) parse any BMFont file to JSON

### parsing

Parses BMFont file formats to a standardized JSON:

- [parse-bmfont-xml](https://www.npmjs.com/package/parse-bmfont-xml)
- [parse-bmfont-ascii](https://www.npmjs.com/package/parse-bmfont-ascii)
- [parse-bmfont-binary](https://www.npmjs.com/package/parse-bmfont-binary)

### writing

Writes to a specific format.

- [write-bmfont-binary](https://www.npmjs.com/package/write-bmfont-binary)

### loading

Handles async loading with fs/XHR in Node/browser.

- [load-bmfont](https://www.npmjs.com/package/load-bmfont) (all formats)

### rendering

- [word-wrapper](https://www.npmjs.com/package/word-wrapper) (left-to-right text)
- [layout-bmfont-text](https://www.npmjs.com/package/layout-bmfont-text)
- [three-bmfont-text](https://www.npmjs.com/package/three-bmfont-text) (ThreeJS)
- [gl-sprite-text](https://www.npmjs.com/package/three-bmfont-text) (stackgl)