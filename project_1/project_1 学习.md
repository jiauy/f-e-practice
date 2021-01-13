# project_1学习
## 非主体部分
### 首行注释信息
```
<!--A Design by W3layouts
Author: W3layout
Author URL: http://w3layouts.com
-->
```
### 声明html协议版本
`<!DOCTYPE HTML>`

### 引入外部文件内容-css
`<link href="css/bootstrap.css" rel='stylesheet' type='text/css' />`
- rel 描述指示被链接的文档是一个样式表 stylesheet这个值被所有浏览器支持，其他的值不被支持，但是显示在代码中，可以`rel='license'表明这个link指向license地址`
### 引入外部文件内容-javascript
`<script type="text/javascript" src="js/jquery.mixitup.min.js"></script>`
### script的type
`<script type="application/x-javascript"></script>`
`<script type="application/javascript"></script>`
`<script type="text/javascript"></script>`
- https://www.cnblogs.com/moyuling/archive/2015/12/01/5011741.html
- 在 HTML5 中，不必加入type=。JavaScript 是 HTML5 以及所有现代浏览器中的默认脚本语言！

## 布局
### div布局
- 7个最外层同级div，每个div具有不同的样式，通过合理的明明，明确每个div的功能。
    - hearder
    - banner
    - banner-bot
    - gallery
    - video-search
    - what-new
    - footer
