
Failing import
==============

If the entry css-file is not located along-side `node_modules` all
`@import`'s from css will fail.

Moving `lib/index.css` to the root and adjusting `package.json` thereafter
works flawlessly! :troll:

```sh
$ npm install bdo-labs/fail-import && npm run build
```

