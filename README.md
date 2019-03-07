# gatsby-source-bigcommerce

This source plugin makes Big Commerce api data available in gatsby.js

## Installation

```
# Install the plugin
yarn add gatsby-source-bigcommerce
```

in `gatsby-config.js`

```
module.exports = {
  plugins: [
    {
      resolve: 'gatsby-source-bigcommerce',
      options: {
        // options
      }
    }
  ]
};
```

## Configuration options

follows node-bigcommerce sdk

example configuration:

```
options: {
  logLevel: 'info',
  clientId: 'yourClientID',
  secret: 'YourClientSecret',
  accessToken: 'yourAccessToken',
  storeHash: 'yourSiteHash',
  endpoint: '/catalog/products'
}
```

## How to query

### TODO

- [ ] implement node-bigcommerce to wrap API
- [ ] implement node-fetch instead of https
- [ ] multiple endpoint support?

#### credit

this is based on [node-bigcommerce](https://github.com/getconversio/node-bigcommerce)
