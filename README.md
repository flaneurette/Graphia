# Graphia Photo editor

<img src="Screen.png" />

[![Try it live](https://img.shields.io/badge/Try%20it-Live-brightgreen)](https://flaneurette.github.io/Graphia/)

A minimalist graphic photo editor to edit and create images, withs drawing tablet support. 4000+ lines of JavaScript code, makes it very portable. Has the most used functions, for simplicity:

Image support:

PNG, JPEG, GIF, AVIF. (except for Firefox, which only support PNG blobs)

Menu:

- Open/save images files. (also: save a selection)
- Preview box
- Magic wand
- Brushes, styles: pencil, round, square, spray, rand. wih dedicated color picker.
- Drag/Pointer
- Resize a layer
- Rectangle
- Circles
- Flood Fill/Bucket
- Color picker
- Zoom +/-
- Text & System Fonts
- Eraser
- Rotate layers (left/right mouse button to rotate direction, snaps into place at certain angles)
- Canvas resizer
- Various standard effects/filters: blur, saturate, neon, hue, contrast, noise, etc.
- Custom Fabrik filters (folded paper, fine grain, rice paper, confetti, etc.)

Right menu:

Layers

- Add layer
- Delete layer
- Merge layers
- Dupe layer
- Move layer

Most popular shortcuts: `ctrl+e` to merge layers, `ctrl+c` to copy layer, `ctrl+v` to paste, `ctrl+x` to cut a layer.

TIP: Use `middle mouse button` to drag layers, or items around.

TIP: Many filters require good hardware. i.e. a fast CPU and GPU. At best, some filters take 3-10 seconds to be applied.

TIP: Firefox browser does not support (yet) anything else but PNG export when using blob.
