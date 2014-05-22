## Git Objects - tree

```
.
├── README
├── app.js
└── lib
    └── math.js
```

README

```
This is a README file.
```

app.js

```
var math = require('./lib/math.js');

console.log(math.add(2, 3));
```

lib/math.js

```
exports.add = function(a, b) {
  return a + b;
};
```
