# eslint-plugin-kimahri

キマリは通さない

## Installation

```bash
npm install --save-dev eslint eslint-kimahri
# or
yarn add -D eslint eslint-plugin-kimahri
```

## Usage

```js
// .eslintrc.js
module.exports = {
  plugins: ["kimahri"],
  rules: {
    "kimahri/not-pass": "error"
  }
};
```

## List of supported rules

- kimahri/not-pass: キマリは通さない
