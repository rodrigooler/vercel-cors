# vercel-cors
Enabling CORS in a single Node.js Serverless Function


# Install

```sh
yarn add https://github.com/rodrigooler/vercel-cors#main
```

# Use

```js
const allowCors = require('vercel-cors')

const handler = (req, res) => {
  const d = new Date()
  res.end(d.toString())
}

module.exports = allowCors(handler)
```
