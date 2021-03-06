canvas-toBlob.js
================

canvas-toBlob.js implements the standard HTML5 [`canvas.toBlob()`][1] and
`canvas.toBlobHD()` methods in browsers that do not natively support it. canvas-toBlob.js
requires `Blob` support to function, which is not present in all browsers. [Blob.js][2]
is a cross-browser `Blob` implementation that solves this.

![Tracking image](https://in.getclicky.com/212712ns.gif)

  [1]: http://www.w3.org/TR/html5/the-canvas-element.html
  [2]: https://github.com/eligrey/Blob.js

Ref: http://updates.html5rocks.com/2011/08/Saving-generated-files-on-the-client-side
