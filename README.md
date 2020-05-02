[![NPM version](https://badge.fury.io/js/less-plugin-rewrite-variable.svg)](http://badge.fury.io/js/less-plugin-rewrite-variable) [![Dependencies](https://david-dm.org/less/less-plugin-rewrite-variable.svg)](https://david-dm.org/less/less-plugin-rewrite-variable)

less-plugin-rewrite-variable
==========================

Less plugin for rewriting variable value

lessc usage
-----------

Install with [npm](https://www.npmjs.com/package/less-plugin-rewrite-variable)

```bash
npm install -g less-plugin-rewrite-variable
```

Programmatic usage
------------------

```js
var RewriteVariablePlugin = require("less-plugin-rewrite-variable"),
    options = {
        plugins: [
            new RewriteVariablePlugin({
                "@textColor": "#000000",
                "@pageBackgound": "#FFFFFF"
            })
        ]
    };

less.render(css, options)
    .then(...);
```
