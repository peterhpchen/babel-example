# preset

* include some plugin.
* env is latest ECMAScript.
* npm install babel-preset-env
* set .babelrc

```js
{
    "presets": [
        [
            "env", {
                "targets": {
                    "browsers": ["last 1 Chrome versions"]
                }
            }
        ]
    ]
}
```