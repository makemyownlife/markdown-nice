<div align="center">
<a href="https://mdnice.com">
<img width="500" src="https://files.mdnice.com/logo.svg"/>
</a>
</div>
<h1 align="center">Markdown Nice</h1>

## 简介

- 支持自定义样式的 Markdown 编辑器
- 支持微信公众号、知乎和稀土掘金
- 欢迎[在线使用](https://mdnice.com/)
- 有疑问请参考 [如何有效的解决 mdnice 相关问题？](https://github.com/mdnice/markdown-nice/issues/163)

## 主题

[Markdown Nice 主题列表](https://product.mdnice.com/themes/)

> 欢迎提交主题，提供更多文章示例~~

## 关于

`mdnice`组建了**推文群**，欢迎反馈意见和公众号大佬们一起交流，关注公众号回复「排版」拉你入群。

| 入群码                                                                                           |
| ------------------------------------------------------------------------------------------------ |
| <img width="360px" src="https://files.mdnice.com/pic/cd3ca20c-896f-4cfc-9bdd-c4c58e69ba26.jpg"/> |

## 友情链接

- [BlogHelper](https://github.com/ystcode/BlogHelper)：一键发布本地文章到主流博客平台的托盘助手
- [qrbtf](https://github.com/ciaochaos/qrbtf)：艺术二维码生成器
- [编程如画](https://draw.mdnice.com/)：「编程如画」博客


> npm run start
> yarn run start

/* 全局属性
* 页边距 padding: 30px;
* 全文字体 font-family: ptima-Regular;
* 英文换行 word-break: break-all;
  */
  #nice {
  font-family:"Avenir, -apple-system-font, 微软雅黑, sans-serif";
  font-size: 15px;
  color:rgb(74,74,74);
  letter-spacing: 0.5444px;
  padding-left: 5px;
  padding-right: 5px;
  padding-top: 0px;
  margin-top: 0px;
  }

/* 段落，下方未标注标签参数均同此处
* 上边距 margin-top: 5px;
* 下边距 margin-bottom: 5px;
* 行高 line-height: 26px;
* 词间距 word-spacing: 3px;
* 字间距 letter-spacing: 3px;
* 对齐 text-align: left;
* 颜色 color: #3e3e3e;
* 字体大小 font-size: 16px;
* 首行缩进 text-indent: 2em;
  */
  #nice p {
  text-align: justify;
  line-height: 30px;
  font-family:"Avenir, -apple-system-font, 微软雅黑, sans-serif";
  font-size:15px;
  color:rgb(74,74,74);
  letter-spacing: 0.5444px;
  padding-top: 0px;
  padding-bottom: 0px;
  margin-bottom:20px;
  }

/* 一级标题 */
#nice h1 {
text-align: center;
margin-top: 35px;
margin-bottom: 20px;
}

/* 一级标题内容 */
#nice h1 .content {
font-size: 16px;
color: rgb(234, 84, 41);
letter-spacing: 0.5444px;
padding-bottom: 10px;
border-bottom: 2px solid rgb(234, 84, 41);
}

/* 一级标题修饰 请参考有实例的主题 */
#nice h1:after {
}

/* 二级标题 */
#nice h2 {
text-align: left;
margin-top: 25px;
margin-bottom: 20px;
}

/* 二级标题内容 */
#nice h2 .content {
color: rgb(171, 25, 66);
font-size:14px;
letter-spacing: 0.5444px;
}

/* 二级标题修饰 请参考有实例的主题 */
#nice h2:after {
}

/* 三级标题 */
#nice h3 {
margin: 0.6em auto;
margin-top: 30px;
color: #1890ff;
}

/* 三级标题内容 */
#nice h3 .content {
font-size: 18px;
letter-spacing: 0.5444px;
}

/* 三级标题修饰 请参考有实例的主题 */
#nice h3:after {
}

/* 四级标题 */
#nice h4 {
margin: 0.6em auto;
font-size: 1.2em;
padding-left: 10px;
border-left: 2px dashed #009688;
margin-top: 30px;
letter-spacing: 0.5444px;
}

/* 五级标题 */
#nice h5 {
margin: 0.6em auto;
font-size: 1.1em;
padding-left: 10px;
border-left: 1px dashed #009688;
}

/* 六级标题 */
#nice h6 {
margin: 0.6em auto;
font-size: 1em;
padding-left: 10px;
border-left: 1px dotted #009688;
}

/* 无序列表整体样式
* list-style-type: square|circle|disc;
  */
  #nice ul {
  list-style-type:square;
  padding-left:1.2em;
  margin-bottom:20px;
  }

/* 有序列表整体样式
* list-style-type: upper-roman|lower-greek|lower-alpha;
  */
  #nice ol {

}

/* 列表内容，不要设置li
*/
#nice li section {
margin-top:0px;
margin-bottom:10px;
line-height:25px;
font-family:"Avenir, -apple-system-font, 微软雅黑, sans-serif";
font-size: 16px;
color:#4A4A4A;
letter-spacing: 0.5444px;
}

/* 引用
* 左边缘颜色 border-left-color: black;
* 背景色 background: gray;
  */
  #nice .multiquote-1 {
  border-left: 2px solid #888;
  padding:8px 10px 8px 15px;
  background:rgb(255, 249, 249);
  border-left-color:rgb(239, 112, 96);
  margin-top: 0px;
  margin-bottom: 10px;
  letter-spacing: 0.5444px;
  }

/* 引用文字 */
#nice .multiquote-1 p {
font-family:"Avenir, -apple-system-font, 微软雅黑, sans-serif";
font-size:14px;
margin-bottom: 10px;
color:rgb(74,74,74);
line-height:30px;
letter-spacing: 0.5444px;
}

/* 链接
* border-bottom: 1px solid #009688;
  */
  #nice a {
  color: #009688;
  border-bottom: 1px solid #009688;
  }

/* 加粗 */
#nice strong {
color: #222222;
font-weight: bold;
letter-spacing: 0.5444px;
}

/* 斜体 */
#nice em {
}

/* 加粗斜体 */
#nice em strong {
}

/* 删除线 */
#nice del {
}

/* 分隔线
* 粗细、样式和颜色
* border-top: 1px solid #3e3e3e;
  */
  #nice hr {
  margin: 20px 0;
  }

/* 图片
* 宽度 width: 80%;
* 居中 margin: 0 auto;
* 居左 margin: 0 0;
  */
  #nice img {
  margin-bottom: 15px;
  }

/* 图片描述文字 */
#nice figcaption {
}

/* 行内代码 */
#nice p code, #nice li code {
color: rgb(234, 84, 41);
}

/* 非微信代码块
* 代码块不换行 display: -webkit-box !important;
* 代码块换行 display: block;
  */
  #nice pre code {
  background: #f8f8f8;
  }

/* 表格内的单元格
* 字体大小 font-size: 16px;
* 边框 border: 1px solid #ccc;
* 内边距 padding: 5px 10px;
  */
  #nice table tr th {
  border: 1px solid #009688;
  background-color: #009688;
  color: #f8f8f8;
  border-bottom: 0;
  }

#nice table tr td {
border: 1px solid #009688;
}

#nice table tr:nth-child(2n) {
background-color: #f8f8f8;
}

/* 脚注文字 */
#nice .footnote-word {
color: #009688;
}

/* 脚注上标 */
#nice .footnote-ref {
color: #009688;
}

/* "参考资料"四个字
* 内容 content: "参考资料";
  */
  #nice .footnotes-sep:before {
  }

/* 参考资料编号 */
#nice .footnote-num {
}

/* 参考资料文字 */
#nice .footnote-item p {
}

/* 参考资料解释 */
#nice .footnote-item p em {
}

/* 行间公式
* 最大宽度 max-width: 300% !important;
  */
  #nice .block-equation svg {
  }

/* 行内公式
*/
#nice .inline-equation svg {  
}

