# js-date

js时间戳转化时间demo

使用方法

getFormatTime.format(Date.parse(new Date())/1000)； // 15:26

getFormatTime.format(1502597545)； // 昨天 12:12

getFormatTime.format(1502390645)； // 2017/08/11 02:44



# 简单小知识


异步加载
-
```
//书上看到直接拿来用下
(function (d, s, id) {
    // 声明一个变量js，并在页面上查找第一个可用的script标签元素赋给fjs 
    var js, fjs = d.getElementsByTagName(s)[0];
    // 判断脚本是否添加到了页面，防止重复加载
    if (d.getElementById(id)) retrun;
    // 创建一个script标签并给其赋值id
    js = d.createElement(s); js.id = id;
    // 设置script标签的地址
    js.src = '//xxx.com/xxx.js';
    // 添加到当前页面的dom
    fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'demo-js-longToDate'));

```


