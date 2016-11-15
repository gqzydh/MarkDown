# MarkDown 入门

- ### Markdown 的优点###

  - 专注你的文字内容而不是排版样式，安心写作。
  - 轻松的导出 HTML、PDF 和本身的 .md 文件。
  - 纯文本内容，兼容所有的文本编辑器与字处理软件。
  - 随时修改你的文章版本，不必像字处理软件生成若干文件版本导致混乱。
  - 可读、直观、学习成本低。

- ### Markdown 工具###

  - Mac OS X -  [Mou](http://mouapp.com/)  ***免费***
  - Windows 
    1. [Typora](http://www.typora.io/)  ***免费*** 
    2.  [MarkdownPad](http://www.markdownpad.com/) 
    3.  [MarkPad](http://code52.org/DownmarkerWPF/) 
  - Linux 平台 - [ReText](http://sourceforge.net/p/retext/home/ReText/) 
  - 在线编辑器
    1. [Markable.in](http://markable.in/)
    2. [Dillinger.io](http://dillinger.io/) 
  - 浏览器插件
    - [MaDe](https://chrome.google.com/webstore/detail/oknndfeeopgpibecfjljjfanledpbkog) (Chrome)

- ## Markdown 语法##

- ### 标题 ###

  > `#`

  ![标题](http://ww1.sinaimg.cn/large/6aee7dbbgw1effeaclhiyj20eh09cwez.jpg)

- ### 列表### 

  > `-` 或 `*`无序列表，有序列表`1.` `2.` `3.` 

  ![img](http://ww4.sinaimg.cn/large/6aee7dbbgw1effew5aftij20d80bz3yw.jpg)

- ### 引用

  >  `>` （大于号） 

  ![img](http://ww3.sinaimg.cn/large/6aee7dbbgw1effezhonxlj20e009c3yu.jpg)

- ### 图片与链接

  > 图片为：`![](){ImgCap}{/ImgCap}`
  >
  > 链接为：`[]()`

![URL 与图片](http://ww2.sinaimg.cn/large/6aee7dbbgw1efffa67voyj20ix0ctq3n.jpg)

- ### 粗体与斜体

  > 两个 `*` 包含一段文本就是粗体的语法。 -  **这里是粗体**
  >
  > 一个 `*` 包含一段文本就是斜体的语法。-  *这里是斜体*

- ### 分隔线

  > 在一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。你也可以在星号或是减号中间插入空格。

  `* * *   ********    - - -            ---------------------------------------`

- ### 强调

  > 用（`*`）和（`_`）作为标记强调字词的符号，被 `*` 或 `_` 包围的字词会被转成用<em> 
  >
  > 用两个 `*` 或`_` 包起来的话，则会被转成 <strong>
  >
  > 如果 * 和 _ 两边都有空白的话，它们就只会被当成普通的符号,
  >
  > 如果要在文字前后直接插入普通的星号或底线，可以用反斜线

- ### 代码

  > 两个 ` 把中间的代码包裹起来

  ![img](https://segmentfault.com/img/bVqmxt)

  ​

- ### 反斜杠

  Markdown 支持以下这些符号前面加上反斜杠来帮助插入普通的符号：

  ```
  \   反斜线
  `   反引号
  *   星号
  _   底线
  {}  花括号
  []  方括号
  ()  括弧
  #   井字号
  +   加号
  -   减号
  .   英文句点
  !   惊叹号
  ```