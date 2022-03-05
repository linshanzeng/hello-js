# js全栈学习笔记

JavaScript是一种运行在浏览器中的解释型的编程语言

## 快速入门

```js
方法一：由<script>...</script>包含
<html>
<head>
  <script>
    alert('Hello, world');
  </script>
</head>
<body>
  ...
</body>
</html>
方法二：把JavaScript代码放到一个单独的.js文件
<html>
<head>
  <script src="/static/js/abc.js"></script>
</head>
<body>
  ...
</body>
</html>
```

请注意，JavaScript严格区分大小写，如果弄错了大小写，程序将报错或者运行不正常。

### 数据类型和变量

```js
1.2345e3; // 科学计数法表示1.2345x1000，等同于1234.5
NaN; // NaN表示Not a Number，当无法计算结果时用NaN表示
Infinity; // Infinity表示无限大，当数值超过了JavaScript的Number所能表示的最大值时，就表示为Infinity

Number：
2 / 0; // Infinity
0 / 0; // NaN
```

## 参考链接

[JavaScript教程](https://www.liaoxuefeng.com/wiki/1022910821149312/1023020895584256)
