# webpack-hot-client-overlay

This is an early prototype.

## Installation

Install package
```
npm install --save-dev @glenjamin/webpack-hot-client-overlay
```

Add to `webpack.config.js`'s `entry` array.

```
entry: [
  "./client",
  mode === "development" && "@glenjamin/webpack-hot-client-overlay"
].filter(Boolean),
```
