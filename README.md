# canvg-client

A port of canvg, which pareses svg input and renders the result to a canvas.
http://code.google.com/p/canvg/

This fork is meant for client-only usage and does not depend on the Canvas package,
which can make problems with platforms such as Heroku.

## Usage
```` js
var canvg = require("canvg");
var canvas = document.createElement('canvas');
canvg(canvas, '<svg></svg>');
