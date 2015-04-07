##  git objects - tree

```
$ git cat-file -p master^{tree}
100644 blob 4169e1c1ba350d389bc1eefd1383b7f171f322c3  README
100644 blob a85668d2d4337284a872dc1f4a323b3ea1561ce3  app.js
040000 tree 6c125dde5a3db92fa24e78988f4231292ad7a7c6  lib
```

```
$ git cat-file -p 6c125dde5a3db92fa24e78988f4231292ad7a7c6
100644 blob e49619f23302d534a70a387256ddfad84870634f  math.js
```

<img src='images/06.png' />
