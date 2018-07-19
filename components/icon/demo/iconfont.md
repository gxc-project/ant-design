---
order: 4
title:
  zh-CN: 使用 iconfont.cn
  en-US: Use iconfont.cn
---

## zh-CN

对于使用 [iconfont.cn](http://iconfont.cn/) 的用户，通过设置 `create` 方法中的 `namespace` 和 `scriptLink` 字段， 即可轻松地使用已有项目中的图标。

## en-US

Todo, please replace me!

````jsx
import { Icon } from 'antd';

const FooIcon = Icon.create({
  namespace: 'foo',
  scriptLink: 'https://at.alicdn.com/t/font_8d5l8fzk5b87iudi.js',
  prefix: 'icon-'
});

ReactDOM.render(
  <div>
    <FooIcon type="tuichu" />
    <FooIcon type="facebook" />
    <FooIcon type="twitter" />
  </div>,
  mountNode
);
````