# gatsby-theme-cart

🛒 A drop-in shopping cart theme for Gatsby

## Install

```bash
yarn add gatsby-theme-cart
```

```js
// In your gatsby-config.js

plugins: [
  {
    resolve: `gatsby-theme-cart`,
  },
]
```

### Options

| Option           | Default | Required | Description                                                                                                           |
| ---------------- | ------- | -------- | --------------------------------------------------------------------------------------------------------------------- |
| `enableCartPage` | `true`  | No       | Disable the automatic `/cart` page. Useful if you wish to use the exported `Cart />` component in your existing page. |
