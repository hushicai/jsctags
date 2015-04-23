```js
define(
    function (require) {
        var l1 = 1;
        var l2 = 2;

        var test = {};

        test.a = 1;

        test.b = 2;

        return test;
    }
);
```
```json
[
  {
    "name": "a",
    "addr": "/a/",
    "kind": "v",
    "type": "number",
    "lineno": 13,
    "namespace": "!define.!requirejs./Users/hushicai/data/test/tern-sample/dep/e"
  },
  {
    "name": "b",
    "addr": "/b/",
    "kind": "v",
    "type": "number",
    "lineno": 15,
    "namespace": "!define.!requirejs./Users/hushicai/data/test/tern-sample/dep/e"
  }
]
```
```ctags
a	/Users/hushicai/data/test/tern-sample/dep/e.js	/a/;"	v	lineno:13	namespace:!define.!requirejs./Users/hushicai/data/test/tern-sample/dep/e	type:number

b	/Users/hushicai/data/test/tern-sample/dep/e.js	/b/;"	v	lineno:15	namespace:!define.!requirejs./Users/hushicai/data/test/tern-sample/dep/e	type:number
```
