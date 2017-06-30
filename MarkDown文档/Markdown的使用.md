# Markdown的使用

## 主要内容

> 好用好写
> 很好使用

## 预览

使用 `CMD + 4` 或者 `CMD + R` 进行分屏预览

## Headers

**Example**

```
# This is an `<h1>` tag
## This is an `<h2>` tag
```

**Result:**
# This is an `<h1>` tag
## This is an `<h2>` tag

## 用于强调

**快捷键** `CMD + U`, `CMD + I`, `CMD + B`
*This text will be italic*
_This will also be italic_ 
**This Text will be bold**
__This will also be bold__
*You **can** combine them*

## 列表

### 无序列表

**快捷键** `Option + U`

**Example:**

* Item 1 unorder list 
* Item 2
* Item 2a unordered list `TAB + * + SPACE`
* Item 2bSPACE`
    * item 1
    * item 2
        * item 1
        * item 2
            * item 1
            * item 2

### 有序列表

1. Item 1 order list `Number + . + SPACE`
2. Item 2
3. Item 3
4.  Item 3a ordered list `TAB + Number + . + SPACE`
    1. hehe
    2. 3heheh
    3. hhh
        1. hehe
        2. item 2

### 任务列表
- [ ] task one not finish 
- [x] task two finished

## 图片

**快捷键** `Control + Shift + I`

![React Logo](http://image.beekka.com/blog/2015/bg2015033101.png) 

可以使用 `-w + Number` 来控制图像大小

![React Logo-w200](http://image.beekka.com/blog/2015/bg2015033101.png) 

## 链接Links

**快捷键** `Control + Shift + L`

[百度链接](http://www.baidu.com)

## 文本块 Blockquotes

**快捷键** 先把文字输入在使用快捷键 `CMD + Shift + B`



就像Kney说的
> 我是谁
> 我来自哪里

## 行间代码

**快捷键** `CMD + K`

I think you should use an `<addr>` `code` 

## 多行代码

**快捷键** `CMD + Shift + K`


```js
function fancyAlert(arg) {
    if (arg) {
        $.facebox({div: '#foo'})
    }
}
```

## 队列和数据流


```sequence
Tom->Jeff: say Hello
Note left of Tom: Jeff thisks about it
Jeff-->Tom: How are you?
Tom->>Jeff: I am good thanks!
```

```flow
st=>start: Start:>http://www.google.com[blank]
e=>end:>http://www.google.com
op1=>operation: My Operation
sub1=>subroutine: My Subroutine
cond=>condition: Yes
or No?:>http://www.google.com
io=>inputoutput: catch something...

st->op1->cond
cond(yes)->io->e
cond(no)->sub1(right)->op1
```

## 表格
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

## 划线

***

*****

- - - 


wotianjia le lingwai 添加一些内容的修改
shkaak
ddkjahdkjdhkjshdk




