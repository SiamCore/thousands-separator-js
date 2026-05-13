# @siamcore/thousands-separator-js
A package to thousands separator

[![npm license](https://img.shields.io/npm/l/@siamcore/thousands-separator-js)](https://www.npmjs.com/package/@siamcore/thousands-separator-js)
[![npm version](https://img.shields.io/npm/v/@siamcore/thousands-separator-js)](https://www.npmjs.com/package/@siamcore/thousands-separator-js)
[![npm download](https://img.shields.io/npm/dt/@siamcore/thousands-separator-js)](https://www.npmjs.com/package/@siamcore/thousands-separator-js)
[![npm download per month](https://img.shields.io/npm/dm/@siamcore/thousands-separator-js)](https://www.npmjs.com/package/@siamcore/thousands-separator-js)
[![npm size](https://img.shields.io/npm/unpacked-size/@siamcore/thousands-separator-js)](https://www.npmjs.com/package/@siamcore/thousands-separator-js)
[![npm bundle size](https://img.shields.io/bundlephobia/min/@siamcore/thousands-separator-js)](https://www.npmjs.com/package/@siamcore/thousands-separator-js)

## Install
```bash
npm i @siamcore/thousands-separator-js
```

## Usage
```javascript
console.log(thousandsSeparator(1000)); // 1,000
console.log(thousandsSeparator(1000, 2)); // 1,000.00
console.log(thousandsSeparator(1000, 2, '')); // 1000.00
console.log(thousandsSeparator(2750.50)); // 2,751
console.log(thousandsSeparator(2750.50, 1)); // 2,750.5
```
