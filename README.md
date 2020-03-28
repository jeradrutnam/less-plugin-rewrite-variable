less-plugin-rewrite-variable
==========================

Less plugin for rewriting variable value

lessc usage
-----------

Install with npm

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
