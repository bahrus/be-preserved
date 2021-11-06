# be-preserved [TODO]

be-preserved is a behavior/decorator alternative to [purr-sist](https://github.com/bahrus/purr-sist)

Example 1:  Isolated storage -- single element / single property

```html
<input be-preserved='{
    "what": {
        "value": "myInputValue"
    },
    "when": ["change"],
    "where": {
        "IBD":{
            "id": "...",
            "path": "a.b.c"
        }
    }
}'>
```