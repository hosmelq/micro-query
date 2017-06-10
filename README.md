# micro-query

> Simple querystring parser for Zeit's [Micro](https://github.com/zeit/micro)

## Install

```
$ npm install --save micro-query
```

## Usage

```js
const query = require('micro-query');

module.exports = async (req, res) => {
  return query(req);
}
```

## License

MIT © [Hosmel Quintana](https://hosmelq.com)
