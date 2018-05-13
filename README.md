# webpack-hot-client-overlay

This is an early prototype which provides an in-browser overlay for use with `webpack-hot-client`.

## Notes

This is mostly a direct copy-paste port of the equivalent code from `webpack-hot-middleware`.

It is currently intended to be good enough for me to use for my own purposes, if this means it's also good enough for you to use, go right ahead.

If you'd like to help make this good enough for everyone else to use, then you might be better off forking this for now, as I'm not sure I have time to contribute properly yet.

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

## License

MIT Licensed
