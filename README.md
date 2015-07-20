# text-modules

A collection of modules for processing, manipulating, and rendering text and fonts in Node and the browser. Please open an issue or submit a PR for suggestions/improvements.

### contents

- [Articles](#articles)
- [Font Processing](#font-processing)
- [Bitmap Text](#bitmap-text)
- [Vector Text](#vector-text)

# <a id="articles" href="#articles">#</a> Articles

- [Material Design on the GPU](http://mattdesl.svbtle.com/material-design-on-the-gpu)
- [Drawing Text with Signed Distance Fields in MapboxGL](https://www.mapbox.com/blog/text-signed-distance-fields/)
- [Improved Alpha-Test Magnification for Vector Textures](https://www.valvesoftware.com/publications/2007/SIGGRAPH2007_AlphaTestedMagnification.pdf)
- [Multi-Channel Distance Field Font Rendering](https://lambdacube3d.wordpress.com/2014/11/12/playing-around-with-font-rendering/)

# <a id="font-processing" href="#font-processing">#</a> Font Processing

- [opentype.js](https://www.npmjs.com/package/opentype.js)
- [freetype2](https://www.npmjs.com/package/freetype2)
- [node-fontnik](https://github.com/mapbox/node-fontnik)

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
- [unpack-bmfonts](https://www.npmjs.com/package/unpack-bmfonts) unpacks a binary of multiple BMFonts 

### writing

Writes to a specific format.

- [write-bmfont-binary](https://www.npmjs.com/package/write-bmfont-binary)
- [pack-bmfonts](https://www.npmjs.com/package/pack-bmfonts) packs multiple BMFonts into a single binary file

### loading

- [load-bmfont](https://www.npmjs.com/package/load-bmfont) loads various BMFont file formats in Node/Browser

### rendering

- [word-wrapper](https://www.npmjs.com/package/word-wrapper) wraps words based on arbitrary 2D glyphs
- [layout-bmfont-text](https://www.npmjs.com/package/layout-bmfont-text) word-wraps and lays out text glyphs
- [three-bmfont-text](https://www.npmjs.com/package/three-bmfont-text) renders BMFont files in ThreeJS
- [gl-sprite-text](https://www.npmjs.com/package/gl-sprite-text) renders BMFont files in stackgl
- [font-atlas](https://github.com/hughsk/font-atlas) populate a Canvas with bitmap font glyphs

### testing

- [bmfont-lato](https://www.npmjs.com/package/bmfont-lato) Lato packed as a BMFont for testing

### misc

- [sdf-bitmap-glyphs](https://www.npmjs.com/package/sdf-bitmap-glyphs)
- [ndarray-bin-pack](https://www.npmjs.com/package/ndarray-bin-pack)
- [distance-transform](https://www.npmjs.com/package/distance-transform)

# <a id="vector-text" href="#vector-text">#</a> Vector Text

### generation

- [vectorize-text](https://www.npmjs.com/package/vectorize-text) render a string to a vectorized cell complex

### triangulation

- [cdt2d](https://www.npmjs.com/package/cdt2d) numerically robust delaunay triangulation
- [earcut](https://www.npmjs.com/package/earcut) small and fast triangulation module
- [triangulate-polyline](https://www.npmjs.com/package/triangulate-polyline) simple abstraction atop `cdt2d`
- [triangulate-contours](https://www.npmjs.com/package/triangulate-polyline) triangulate using Tess2

### curves

- [cubic-hermite-spline](https://www.npmjs.com/package/cubic-hermite-spline)
- [b-spline](https://www.npmjs.com/package/b-spline)
- [bezier-curve](https://www.npmjs.com/package/bezier-curve)
- [adaptive-bezier-curve](https://www.npmjs.com/package/adaptive-bezier-curve)
- [adaptive-quadratic-curve](https://www.npmjs.com/package/adaptive-quadratic-curve)
- [cat-rom-spline](https://www.npmjs.com/package/cat-rom-spline)
- [bezier-easing](https://www.npmjs.com/package/bezier-easing)

### paths

- [simplify-path](https://www.npmjs.com/package/simplify-path) - simplify using radial distance and Douglas-Peucker 
- [chaikin-smooth](https://www.npmjs.com/package/chaikin-smooth) - Chaikin's smoothing algorithm for a polyline
- [robust-orientation](https://www.npmjs.com/package/robust-orientation) and [is-clockwise](https://www.npmjs.com/package/is-clockwise) for polygon orientation