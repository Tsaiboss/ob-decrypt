# ob-decrypt

通过操作AST，还原被obfuscator工具混淆了的JavaScript代码

# 使用方法

1.网上复制经过obfuscator工具混淆了的JavaScript代码，保存为js文件

格式:UTF-8

文件名:encode_code.js


2.将encode_code.js 与本仓库的 obfuscator_decode.js 文件放在同一个目录下

3.运行 obfuscator_decode.js 文件，命令：node obfuscator_decode.js

4.结果保存在 decode_code.js文件里，打开即可以看到解混淆后的代码。



欢迎关注本人微信公众号:菜鸟学Python编程

![image.png](https://cdn.nlark.com/yuque/0/2020/png/598650/1591971225499-565d5b59-1a15-45a5-8643-9937c5725d23.png#align=left&display=inline&height=215&margin=%5Bobject%20Object%5D&name=image.png&originHeight=430&originWidth=430&size=75528&status=done&style=none&width=215)


1.nodejs环境搭建，全局安装babel库。

2.通过在线解析网站认识AST结构。

3.在线学习JavaScript编程及AST相关网站收集。

4.认识path及其node属性。

5.path常用方法介绍。

6.scope常用方法介绍。

7.操作AST(babel库)常用的代码结构。

8.如何获取path/node 节点源代码。

9.如何构造节点

10.如何删除节点

11.如何插入节点。

12.如何处理十六进制字符串以及unicode。

13.如何删除所有的代码注释。

14.如何删除多余的空行，空语句

15.如何删除未被使用的变量(由var,let,const定义)。

16.如何删除未被调用的函数。

17.如何还原定义的字面量(由var等定义，初始值被改变)。

18.如何还原Array对象。

19.如何还原object对象。

20.如何处理eval表达式。

21.如何优雅的计算常见的表达式，如1+2,!![],"string".length等。

22.如何在函数调用处自动替换计算值。

23.如何还原实参。

24.如何处理自执行函数。

25.如何将逗号表达式拆分为多个语句。

26.如何去控制流(for-switch)。

27.如何去控制流(while-switch)。

28.如何处理条件已知的if、三目表达式语句。

29.修改源码，兼容处理 "string"["length"]结构的表达式。

30.修改源码，兼容处理parseInt、decodeURIComponent等全局函数。

31.如何合并相同结构的表达式。

32.如何合并定义在object对象外面的key、value。

33.如何使用AST处理ob混淆的内存爆破代码。

34.一个小例子搞懂enter(默认)与 exit 的区别。

35.如何把 a = m?11:22; 转成 m ? a = 11 : a = 22;。

36.如何对多个节点使用同一方法。

37.如何对同一节点使用多个方法。

38.三目表达式拆分为if语句。
