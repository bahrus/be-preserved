# be-preserved [TODO]

be-preserved is a behavior/decorator alternative to [purr-sist](https://github.com/bahrus/purr-sist)

Example 1:  Default settings;

```html
<input be-preserved be-revived>
```

What this does:

Stores input's value in session storage (key is based on location within the dom).

be-revived sets the value based on the value in session storage.

Example 2:  Isolated storage -- single element

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