# remote-json-loader

> webpack remote json loader

## Installation

```sh
npm i remote-json-loader --save-dev
```

## Usage

```js
import config from 'remote-json?app-config!./config.json';

// config.json
{
  "app-config": "http://my-website.ninja/config.json",
  "ui-config": "http://my-website.ninja/interface-config.json"
}
```

## License

MIT © [Michał Jezierski](https://github.com/msn0)
