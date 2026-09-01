# 练习 3：HTML5 文档结构与文本格式化标签 | Practice 3: HTML5 Document Structure and Text Formatting Tags

## 目标 | Objective
- 掌握完整的 HTML5 文档标准结构（DOCTYPE, html, head, body）。 | Master the complete HTML5 document standard structure.
- 理解并应用语义化标签（h1, h2, p）组织网页内容。 | Understand and apply semantic tags (h1, h2, p) to organize webpage content.
- 学习使用 `<hr>` 水平分割线和 `<br>` 换行标签进行页面排版。 | Learn to use `<hr>` horizontal rule and `<br>` line break tags for page layout.
- 了解前端开发的核心技术栈及其发展历程。 | Learn the core technology stack and development history of frontend development.

## 代码结构 | Code Structure
```html
<!DOCTYPE html> <!-- 声明文档类型为 HTML5 -->
<html lang="zh-CN"> <!-- 设置网页语言为简体中文 -->
<head>
    <meta charset="UTF-8"> <!-- 设置字符编码，防止中文乱码 -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- 响应式视口设置 -->
    <title>网页标题</title>
</head>
<body>
    <h1>前端开发</h1> <!-- 一级标题 -->
    <h2>（引用自百度）</h2> <!-- 二级标题 -->
    <hr> <!-- 水平分割线 -->
    <p>前端开发是创建Web页面或App等前端界面呈现给用户的过程...
        <br>核心框架包括Vue.js、React等... <!-- 换行标签 -->
        HTML负责内容结构，CSS控制视觉样式...
        <br>依托HTML5与Node.js等技术扩展跨平台应用能力...</p> <!-- 换行标签 -->
    <p>该领域起源于Web1.0时代的静态网页制作...
        <br>移动互联网时代催生了移动终端适配...</p> <!-- 换行标签 -->
</body>
</html>