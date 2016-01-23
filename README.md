# is-pjl

Check if a given `Buffer` or `Uint8Array` is a
[PJL](https://en.wikipedia.org/wiki/Printer_Job_Language) document.

## Installation

```
npm install is-pjl --save
```

## Usage

```js
var isPjl = require('is-pjl')
var buf = fs.readFileSync('doc.pjl')

if (isPjl(buf)) {
  console.log('The data is a PJL document')
}
```

## License

MIT
