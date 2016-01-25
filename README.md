# credicard.js

[![Build Status](https://api.travis-ci.org/DomPhysis/credicard.js.svg?branch=master)](https://travis-ci.org/DomPhysis/credicard.js)

> A simple library for validation of credit cards in JavaScript.

## Install

You can [download the minified file](link) or use NPM and Bower.

### NPM

```
npm install --save-dev creditcard.js
```

### Bower

```
bower install creditcard.js --save
```

For CDN use, check [this link](link).

## Usage

In browser:

```javascript
var obj = new CreditCard();
obj.getCreditCardNameByNumber('4539578763621486'); // return 'Visa'
```

In server:

```javascript
var creditcard = require('dist/node/creditcard.js');
credit.getCreditCardNameByNumber('4539578763621486'); // return 'Visa'
```

### Methods

#### obj`.validadeExpiryDate()`

Returns whether the value is `true` or `false`.

#### obj`.validadeCreditCard()`

Returns whether the value is `true` or `false`.

#### obj`.validadeSecuryCode()`

Returns whether the value is `true` or `false`.

#### obj`.getCreditCardNameByNumber()`

Returns a `String` with the credit card name.

## Browser support

| <img src="http://i.imgur.com/dJC1GUv.png" width="48px" height="48px" alt="Chrome logo"> | <img src="http://i.imgur.com/o1m5RcQ.png" width="48px" height="48px" alt="Firefox logo"> | <img src="http://i.imgur.com/8h3iz5H.png" width="48px" height="48px" alt="Internet Explorer logo"> | <img src="http://i.imgur.com/iQV4nmJ.png" width="48px" height="48px" alt="Opera logo"> | <img src="http://i.imgur.com/j3tgNKJ.png" width="48px" height="48px" alt="Safari logo"> |
|:---:|:---:|:---:|:---:|:---:|
| Latest ✔ | Latest ✔ | 9+ ✔ | Latest ✔ | 8+ ✔ |

## Development

// todo

## License

MIT
