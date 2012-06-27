# node-xui

An npm package wrapper for the awesome [xui.js](http://xuijs.com).

This currently doesn't work on the server, only the browser. I am using it to create client side onejs apps that use xui 
explicitly (and not assuming it is in the global namespace).

TODO:
 * Support using jsdom to bind it to a server side document.

## Install

Install with npm:

```bash
$ npm install xui
```

Bundle with [onejs](https://github.com/azer/onejs).

## Usage

```javascript
var x$ = require('xui');
x$('bla').havefun();
```

See [xui.js](http://xuijs.com) for documentation.

# License

## xui.js

[License](http://xuijs.com/license)

## node-xui

(The MIT License)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
