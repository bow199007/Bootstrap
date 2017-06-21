# Bootstrap
Bootsratp学习实例
只作为每章单独学习所写的例子
例子中没有做IE8的兼容性处理
针对IE8兼容处理，使用以下代码：
```
<!--[if lt IE 9]>
<script src="https://cdn.bootcss.com/html5shiv/3.7.3/html5shiv.min.js"></script>
<script src="https://cdn.bootcss.com/respond.js/1.4.2/respond.min.js"></script>
<![endif]-->
```
注意这里的respond.min.js
由于浏览器的安全机制，Respond.js 不能在通过 file:// 协议（打开本地HTML文件所用的协议）访问的页面上发挥正常的功能。如果需要测试 IE8 下面的响应式特性，务必通过 http 协议访问页面（例如搭建 apache、nginx 等）



