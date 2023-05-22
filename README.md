
# CodeMirror 6 - TextToLink Extension

This is an extension for CodeMirror 6 to add a clickable link icon next to a valid URL.

## Demo

**[Demo On GitHub Page](https://a99us.github.io/CM6-Browser-Wrapper/)**

## How To Use

First you need to add the extension :

```console
npm i cm6-texttolink
```

And then import the function :

```javascript
import { TextToLink, hyperLinkStyle } from 'cm6-texttolink'
```

And then you can add the functions to extension array : 

```javascript
let extension = [ basicSetup, TextToLink(EditorView), hyperLinkStyle ];
```

## Credit

SVG Icon and CSS style are from [@uiwjs/react-codemirror/hyper-link](https://github.com/uiwjs/react-codemirror/tree/master/extensions/hyper-link)

## License

MIT
