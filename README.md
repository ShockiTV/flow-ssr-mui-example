pull request to fix issue created with breaking changes in [meteor's `react` package](https://github.com/meteor/react-packages/tree/master/packages/react)

>`W20150811-02:11:13.016(-4)? (STDERR) TypeError: Cannot read property 'require' of undefined`
>`W20150811-02:11:13.017(-4)? (STDERR)     at Object.<anonymous> (packages/node_modules/material-ui/lib/app-bar.js:3:1)`
>`W20150811-02:11:13.017(-4)? (STDERR)     at Object../icon-button (packages/node_modules/material-ui/lib/app-bar.js:220:1)`

--
Read about it here!! https://github.com/meteor/react-packages/issues/83

---


Hello fellow Meteor users :D

This is my little experiment to combine:
flow-router-ssr
material-ui

I just modified izzilab:material-ui package to work with current SSR.
At least for the example usage.

Have fun
