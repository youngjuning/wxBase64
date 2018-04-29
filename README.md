# wxBase64

## 引入

### node.js

```js
let Base64 = require('js-base64').Base64
```

### es6+

```js
import {Base64} from '/utils/base64.min.js'
```

## 使用

```js
Base64.encode('youngjuning');  // eW91bmdqdW5pbmc=
Base64.encode('杨俊宁');    // 5p2o5L+K5a6B
Base64.encodeURI('杨俊宁'); // 5bCP6aO85by-

Base64.decode('eW91bmdqdW5pbmc=');  // youngjuning
Base64.decode('5p2o5L+K5a6B');  // 杨俊宁
// note .decodeURI() is unnecessary since it accepts both flavors
Base64.decode('5bCP6aO85by-');  // 杨俊宁
```

## 感谢

感谢 dankogai [![GitHub followers](https://img.shields.io/github/followers/dankogai.svg?style=social&label=Follow)](https://github.com/dankogai) 开发了 js-base64 [![GitHub stars](https://img.shields.io/github/stars/dankogai/js-base64.svg?style=social&label=Stars)](https://github.com/dankogai/js-base64)
