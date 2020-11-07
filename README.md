<h1 align="center">Welcome to cadena-romano-a-decimal 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/chitenavi/cadena-romano-a-decimal#readme" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/chitenavi/cadena-romano-a-decimal/graphs/commit-activity" target="_blank">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" />
  </a>
  <a href="https://github.com/chitenavi/cadena-romano-a-decimal/blob/master/LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/github/license/chitenavi/cadena-romano-a-decimal" />
  </a>
</p>

> Convert literal roman number to decimal number

### 🏠 [Homepage](https://github.com/chitenavi/cadena-romano-a-decimal#readme)

## Install

```sh
npm install cadena-romano-a-decimal
```

## Usage

First, import module:

```js
const numRomanoAdecimal = require('cadena-romano-a-decimal');
```

Then you can use the convert function in your app:

```js
const romanString = 'XXI';
const valueDecimal = numRomanoAdecimal(romanString);

if (valueDecimal !== -1) {
  console.log(`${romanString} is ${valueDecimal}`);
} else {
  console.log(`Invalid roman literal!!`);
}
```

## Author

👤 **Ivan Chinea**

- Github: [@chitenavi](https://github.com/chitenavi)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/chitenavi/cadena-romano-a-decimal/issues). You can also take a look at the [contributing guide](https://github.com/chitenavi/cadena-romano-a-decimal/blob/master/CONTRIBUTING.md).

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2020 [Ivan Chinea](https://github.com/chitenavi).<br />
This project is [MIT](https://github.com/chitenavi/cadena-romano-a-decimal/blob/master/LICENSE) licensed.
