![logo](https://github.com/schmittsfn/BiDictionary/assets/1940017/abe75c9d-0493-44b7-9c4c-ab486dbab2a2)


A bi-directional dictionary/map for the Swift programming language.


Usage:
```
var biDict = BiDictionary<String, String>()
biDict[key: "foo"] = "bar"

let value = biDict[key: "foo"]
let key = biDict[value: "bar"]
```

