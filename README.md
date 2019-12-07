## 关于mUtils

[文档地址](https://alie-z.github.io/mUtils/#/)

#### 产生背景
这是关于个人日常比较通用代码的收集

#### 功能描述
该方法一共包含以下属性，每个属性收集了对应的方法内容

- `DomUtils`
  该属性主要时针对dom元素相关的方法，针对于元素的一些操作

- `DeviceUtils`
  设备相关的检测与方法

- `StoreUtils`
  该属性主要是对于数据的操作

- `HttpRequestUtils`
  基于axios请求的封装

- `ExpUtils`
  该属性是d-js-utlis里的一个类，此属性包含对于一些字符，或者元素判断是否符合要求

- `GenericUtils`
  其他相关js工具代码，通用工具类

- `LogUtils`
  日志相关

- `PerformanceUtils`
  浏览器性能相关

- `UrlUtils`
  url地址的一系列操作

- `WeixinUtils`
  微信jssdk相关的方法

- `ImageUtils`
  图片合成相关


# 快速使用
#### 安装
使用npm安装 `mUtils` 依赖
```bash
npm i mUtils
```
yarn
```hash
yarn add mUtils
```
#### 使用
获取所有方法
```js
import mUtils from 'mUtils'
Dutils.DomUtils.addClass(document.body, 'mUtils')
```
按需引入
```js
import { DomUtils, LogUtils } from 'mUtils'
DomUtils.addClass(document.body, 'mUtils')
LogUtils.logInfo('mUtils')
```

直接引用js
```html
<script src=""></script>
<script>
  mUtils.DomUtils.addClass(document.body, 'mUtils')
</script>
```
```js
mUtils.DomUtils.cssFilter(document.body, 'grayscale', 1)
```

