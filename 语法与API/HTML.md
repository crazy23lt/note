# HTML（超文本标记语言——HyperText Markup Language）

> 构成 Web 世界的一砖一瓦

## 基础标签

```html
<!DOCTYPE html>
<!-- 文档类型 -->
<html leng="en">
  <!-- 含整个页面的内容，也称作根元素 -->
  <head>
    <!-- 该元素的内容对用户不可见，其中包含例如面向搜索引擎的搜索关键字（keywords）、页面描述、CSS 样式表和字符编码声明等。 -->
    <meta charset="UTF-8" />
    <!--  该元素指定文档使用 UTF-8 字符编码 -->
    <title>Document</title>
    <!-- 页面的标题 -->
  </head>
  <body></body>
  <!-- 用户在访问页面时看到的内容 -->
</html>
```

### 块级元素与行内元素

| 元素类型 | 独占一行 | 高度、行高、内外边距 |      宽度      |     嵌套子元素 |
| :------- | :------: | :------------------: | :------------: | -------------: |
| 块级元素 |    是    |        都可控        |  父容器 100%   |     块级、行内 |
| 行内元素 |    否    |        不可控        | 文字或图片宽度 | 文本或其他行内 |

### 单标签与双标签

| 标签类别 |                                                         标签汇总                                                          |
| :------- | :-----------------------------------------------------------------------------------------------------------------------: |
| 单标签   |                                   `<br>、<hr>、<img>、<input>、<param>、<meta>、<link>`                                   |
| 双标签   | `<html>、<head>、<title>、<body>、<table>、<tr>、<td>、<th>、<span>、<p>、<form>、<h1>、<object>、<style>、<b>、<strong>` |

## 媒体标签

## 图形标签

## Reference

- [HTML 基础](https://developer.mozilla.org/zh-CN/docs/Learn/Getting_started_with_the_web/HTML_basics)

- [HTML 单标签双标签汇总](http://www.mabiji.com/html/htmltag.html)
