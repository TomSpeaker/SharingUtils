# HMarkIt文档

### 需求

网上不太好找到将.md格式的文件，转换为html标签，便于显示到页面，由此根据typera的文件，制作了将typera.md文件转换为html页面标签的功能包

## 部分完成

目前只支持

标题语法#

强调语法\*\*我\*\*

引用语法>

列表语法

分割线语法\-\-\-\-\-\-

连接语法\[\]\(\)

图片语法\!\[\]\(\)

以及转义字符语法

支持内嵌的table,Html语法

## 使用教程

下载好jar包后

导入jar包后

使用

MarkIt.*MdToHtml*("##This is right")

可得到

<h2>This is right</h2>

## This is right

可以使用MarkItUtils.*ReadFile*(路径);读取md文件，返回String,直接放入MarkIt.*MdToHtml*即可

记得引入HmarkIt.css