## 动态调查问卷生成系统

### About

此系统为动态调查问卷生成系统,即百度前端技术学院最终任务。近期老师正好要求做一个这样的系统,所以自己加了后台,
实现上可能跟要求有些区别。问卷编辑上,完成了对题目的动态添加,样式修改。包括下划文本线,输入框,以及表格的动态
拖拽。表格完全自定义,支持合并行,和并列,自定义大小,规格。也可根据内嵌文字的长短自动改变大小。还支持对调查结
果导出Excel表格具体页面有操作介绍。

### ScreenShot

![](screenshot.png)

### Use

1.UI系统界面使用Bootstrap完成.

2.原生JS+一点JQuery.

3.新学习了Sass的使用,所以自己写的css都是用sass完成的.

4.后台框架是常用的Spring Mvc+Spring+Mybatis

5.数据库使用Mysql

### Function

1.管理员登录,进入后台管理数据,包括

(1)根据自定义条件录入题目

(2)管理题目

(3)生成调查问卷

(4)查看调查结果,打印Excel文件

(5)管理管理员

2.用户根据自己性别答题

### Difficulty

本次系统制作难点在于表格的自定义生成,没找到插件,只能自己写了一套,难点在于如何实现表格的动态合并行,和并列。
