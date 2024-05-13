# dollariz
node package that helps convert cents into dollars specially when working in APIs

## How to install
`npm install dollariz@latest`

## How to use

```
const dollars = require("dollariz");

const cents = 15080;
const dollars = dollars. convertToDollars(cents, decimal=2);

console.log(dollars);
:150.80
```
by defailt dollariz uses 2 decimals so you dont have to specify but if you need to use a different decimal value then you can specify 
