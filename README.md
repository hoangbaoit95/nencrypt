# nencrypt
A port of [JSEncrypt](https://github.com/travist/jsencrypt) to NodeJS.

## Installation
    $ npm install nencrypt --save
    
[![NPM](https://nodei.co/npm/nencrypt.png?downloads=true&stars=true)](https://nodei.co/npm/nencrypt/)
    
## Examples
```js
// Example RSA encryption
var JSEncrypt = require("node-jsencrypt");
var encrypt = new JSEncrypt();
encrypt.setPublicKey(publicKey);
encrypted = encrypt.encrypt(data);
```