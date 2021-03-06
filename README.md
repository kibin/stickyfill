# Stickyfill

A polyfill for `position: sticky` for browsers that don't support it yet.

Essentially [wilddeer/stickyfill](https://github.com/wilddeer/stickyfill) wrapped as a webmodule.

## Differences

Original polyfill clone is always a 'div', this fork allows you to use params (only tagName for now)

## Installation

```bash
npm install stickyfill
```

## Usage

```javascript
var Stickyfill = require('stickyfill');

// you can optionally pass `document` and `window` for reuse in iframes
var stickyfill = Stickyfill();

// make sure to add the elements you want to polyfill
stickyfill.add(el);
```

For more detailed information, see the [original Readme.md file](https://github.com/wilddeer/stickyfill/blob/master/README.md) on the [wilddeer/stickyfill](https://github.com/wilddeer/stickyfill) repo.

## Acknowledgements

Thanks to Oleg Korsunsky ([@wilddeer](https://github.com/wilddeer)), for the excelent polyfill implementation.

## License

MIT License
