# Storybook SVGR React Componentss
This plugin will add the same CRA useful behaviour on storybook regarding SVG.

For using it:
1. run `npm install -D storybook-svgr-react-component` or `yarn add -D storybook-svgr-react-component`.
1.just add the following plugin on your `./storybook/main.js`:

```diff
  module.exports = {
    addons: [
+     'storybook-svgr-react-component',
    ]
  }

```