# promise-mini-api

小程序 API 的 promise 封装。

支持的小程序：

  - 阿里（支付宝）小程序
  - 微信小程序
  - 字节跳动小程序

## 安装

```bash
$ npm install promise-mini-api --save
```

## 使用

```js
import { getLocation } from 'promise-mini-api/ali';
// import { getLocation } from 'promise-mini-api/wechat';
// import { getLocation } from 'promise-mini-api/toutiao';

const res = await getLocation();
console.log(res);
```

## LICENSE

[MIT](./LICENSE)
