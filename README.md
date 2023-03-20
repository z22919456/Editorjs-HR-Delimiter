![](https://badgen.net/badge/Editor.js/v2.0/blue)

# Delimiter Tool for Editor.js (Hr tag Version)

Delimiter Tool for the [Editor.js](https://editorjs.io).

This tool is a modification of the @editorjs/delimiter library that replaces the asterisk separators in the original library with horizontal lines.


## Installation

### Install via NPM

Get the package

```shell
npm i --save-dev editorjs_delimiter
```

Include module at your application

```javascript
const Delimiter = require('editorjs_delimiter');
```

### Download to your project's source dir

1. Upload folder `dist` from repository
2. Add `dist/bundle.js` file to your page.


## Usage

Add a new Tool to the `tools` property of the Editor.js initial config.

```javascript
var editor = EditorJS({
  ...
  
  tools: {
    ...
    delimiter: Delimiter,
  }
  
  ...
});
```

## Config Params

This Tool has no config params

## Output data

This Tool returns empty object.

```json
{
    "type" : "delimiter",
    "data" : {}
}
```

