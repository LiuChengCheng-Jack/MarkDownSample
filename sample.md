语法链接：https://www.appinn.com/markdown/#html
# Welcome to MarkdownPad 2 #
## Welcome to MarkdownPad 2 ##
### Welcome to MarkdownPad 2 #
#### Welcome to MarkdownPad 2 ##
##### Welcome to MarkdownPad 2 #
####### Welcome to MarkdownPad 2 ##

##引用
> ####这是一个标题。
> 
> 1.   引用示例（引用中换行要使用>）。
> 2.   有序列表示例。
> 3.   可以在引用中使用标题
> 
> 给出一些例子代码：
> 
>     printf("要使用五个空格表示这种代码段形式");

##列表

1.  This is a list item with two paragraphs. Lorem ipsum dolor
    sit amet, consectetuer adipiscing elit. Aliquam hendrerit
    mi posuere lectus.（绿色代表同属于上一个列表，列表项目
    可以包含多个段落，每个项目下的段落都必须缩进 4 个空格或是 1 个制表符
    其实每个段落格式只与第一行相关）

    Vestibulum enim wisi, viverra nec, fringilla in, laoreet
    vitae, risus. Donec sit amet nisl. Aliquam semper ipsum
    sit amet velit.     

割裂列表（为了割裂列表，需要在中间加入一段文字，或者加一个#类型标题）

- A list item with a blockquote:

    > 列表内引用（需要四个空格）
 
* 一列表项包含一个区块代码：
        
        <代码写在这（8 个空格或是 2 个制表符）>

+ 三种非有序列表方式（注意与正文有一个空格）     

##割裂列表，代码段##
 
    printf("代码段在正文中只需要四个空格");

割裂区块代码也需要顶格写一段文字隔开，因为一个代码区块会一直持续到没有缩进的那一行

    tell application "Foo"
        beep
    end tell

    代码区块中，一般的 Markdown 语法不会被转换，像是星号便只是星号，这表示你可以很容易地以 Markdown 语法撰写 Markdown 语法相关的文件。所见即所得
    <div class="footer">
        &copy; 2004 Foo Corporation
    </div>

##分割线的用法
你可以在一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。

---
___
***
##链接的用法

Markdown 支持两种形式的链接语法： __行内式__和__参考式__两种形式。

不管是哪一种，链接文字都是用 [方括号] 来标记。

要建立一个行内式的链接，只要在方块括号后面紧接着圆括号并插入网址链接即可，如果你还想要加上链接的 title 文字，只要在网址后面，用双引号把 title 文字包起来即可，例如：

This is [an example](http://example.com/  "Title") inline link.

关于**参考式形式**类似于代码复用，可以理解为链接复用，适合于多个链接到同一地址的情况

##图片
Markdown 使用一种和链接很相似的语法来标记图片，同样也允许两种样式： __行内式__和__参考式__

参考式可以之后使用时才了解，__行内式__的图片语法看起来像是：

	![Alt text](/path/to/img.jpg)

	![Alt text](/path/to/img.jpg "title")
![猫咪](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1544868851&di=19fcf13f5aaa37c0e754bc8716a55690&imgtype=jpg&er=1&src=http%3A%2F%2Fb-ssl.duitang.com%2Fuploads%2Fitem%2F201502%2F05%2F20150205122709_4MwuL.jpeg "猫咪")

##其他习惯用法
- 分段中间要有一个空行

- **加粗**字体

- 字体加背景（`背景背景`），可标记一小段代码`printf("一小段代码")`

- 自动链接

    Markdown 支持以比较简短的自动链接形式来处理网址和电子邮件信箱，只要是用方括号包起来， Markdown 就会自动把它转成链接。一般网址的链接文字就和链接地址一样，例如：

    <http://example.com/>

- \*  开头的段落可以用加反斜杠

    Markdown 支持以下这些符号前面加上反斜杠来帮助插入普通的符号：

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

 
