# phantomjs-polyfill-includes
A simple Array.prototype.includes polyfill to phantomJS command line browser. Based in MDN specification

MIT License

## Installation

```
    npm install --save-dev phantomjs-polyfill-includes
```

## Usage with Karma

Include the polyfill directly in the files list of your karma.conf.

```
    ...
    files: [
      './node_modules/phantomjs-polyfill-includes/includes-polyfill.js',
      ...
    ]
    ...
```