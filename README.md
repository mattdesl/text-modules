# text-modules

A collection of modules for processing, manipulating, and rendering text and fonts in Node and the browser. Please open an issue or submit a PR for suggestions/improvements.

### contents

- [Font Processing](#font-processing)
- [Bitmap Text](#bitmap-text)
- [Vector Text](#vector-text)

# <a id="font-processing" href="#font-processing">#</a> Font Processing

- [opentype.js](https://www.npmjs.com/package/opentype.js)
- [freetype2](https://www.npmjs.com/package/freetype2)

# <a id="bitmap-text" href="#bitmap-text">#</a> Bitmap Text

### generation tools

- [BMFont](http://www.angelcode.com/products/bmfont/) (Windows only)
- [Hiero](https://github.com/libgdx/libgdx/wiki/Hiero)
- [GlyphDesigner](https://71squared.com/glyphdesigner)
- [Littera](http://kvazars.com/littera/)
- [gdx-fontpack](https://github.com/mattdesl/gdx-fontpack)
- [bmGlyph](http://www.bmglyph.com/)

### command-line tools

- [image-sdf](https://www.npmjs.com/package/image-sdf) get an image's Signed Distance Field
- [convert-bmfont](https://www.npmjs.com/package/convert-bmfont) convert BMFont from one format to another

### parsing

Parses BMFont file formats to a [standardized JSON](https://github.com/Jam3/load-bmfont/blob/master/json-spec.md).

- [parse-bmfont-xml](https://www.npmjs.com/package/parse-bmfont-xml)
- [parse-bmfont-ascii](https://www.npmjs.com/package/parse-bmfont-ascii)
- [parse-bmfont-binary](https://www.npmjs.com/package/parse-bmfont-binary)

### writing

Writes to a specific format.

- [write-bmfont-binary](https://www.npmjs.com/package/write-bmfont-binary)

### loading

- [load-bmfont](https://www.npmjs.com/package/load-bmfont) loads various BMFont file formats in Node/Browser

### rendering

- [word-wrapper](https://www.npmjs.com/package/word-wrapper) wraps words based on arbitrary 2D glyphs
- [layout-bmfont-text](https://www.npmjs.com/package/layout-bmfont-text) word-wraps and lays out text glyphs
- [three-bmfont-text](https://www.npmjs.com/package/three-bmfont-text) renders BMFont files in ThreeJS
- [gl-sprite-text](https://www.npmjs.com/package/gl-sprite-text) renders BMFont files in stackgl

### testing

- [bmfont-lato](https://www.npmjs.com/package/bmfont-lato) Lato packed as a BMFont for testing

# <a id="vector-text" href="#vector-text">#</a> Vector Text

- [vectorize-text](https://www.npmjs.com/package/vectorize-text) render a string to a vectorized cell complex
- [earcut](https://www.npmjs.com/package/earcut) small and fast triangulation module
- [triangulate-polyline](https://www.npmjs.com/package/triangulate-polyline) triangulate using poly2tri
- [triangulate-contours](https://www.npmjs.com/package/triangulate-polyline) triangulate using Tess2
- [adaptive-bezier-curve](https://www.npmjs.com/package/adaptive-bezier-curve) adaptive cubic/quadratic curves
- [simplify-path](https://www.npmjs.com/package/simplify-path) - simplify using radial distance and Douglas-Peucker 
- [chaikin-smooth](https://www.npmjs.com/package/chaikin-smooth) - Chaikin's smoothing algorithm for a polyline
- [robust-orientation](https://www.npmjs.com/package/robust-orientation) and [is-clockwise](https://www.npmjs.com/package/is-clockwise) for polygon orientation
