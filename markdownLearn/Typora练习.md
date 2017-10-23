# 一级标题

## 二级标题

### 三级标题

#### 四级标题

##### 五级标题

###### 六级标题



###### *斜体*或_斜体_

**粗体**

***加粗斜体***

~~删除线~~



这是一个一级标题

===========================================

这是一个二级标题

------------------------------------------------



欢迎来到[饭局闹事](http://blog.leanote.com/freewalk)

欢迎来到[饭局闹事](http://blog.leanote.com/freewalk "饭局闹事")



我经常去的几个网站[Google][1]、[Leanote][2]以及[我的博客][]。

[Leanote 笔记][2]是一个不错的[网站][]。

[1]:http://www.google.com "Google Home Page"
[2]:http://www.leanote.com "Leanote"
[我的博客]:http://blog.csdn.net/chenjun15 "陈俊的博客"
[网站]:http://blog.leanote.com/freewalk

## 0.目录{#index}



## 跳转到[目录](#index)

- 无序列表项一
- 无序列表项二



1. 有序列表项一
2. 有序列表项二



Markdown

:    轻量级文本标记语言，可以转换成html，pdf等格式



代码块 2

:	这是代码块的定义



​        代码块



This paragraph has a quote

> That is pulled out like this

from the text my post.



This is a paragraph that contains a [link to example]()



This paragraph contains a list of items.

* Item 1
* Item 2

图片![美女]()

`alert('Hello World')`

```
#include <stdio.h>

int main()
{
  printf("Hello World!\n");
  return 0;
}
```



> This is a blockquote with two paragraphs. This is first paragraph.
>
> 
>
> This is second pragraph.Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.



> This is another blockquote with one paragraph. There is three empty line to seperate two blockquote.

- [ ] a task list item
- [ ] list syntax required
- [ ] normal **formatting**, @mentions, #1234 refs
- [ ] incomplete
- [x] completed

```C++
#include <iostream>
using namespace std;

int main(int argc, char *argv[])
{
    cout << "Hello World" << endl;
}
```

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
$$
\mathbf{V}_1 \times \mathbf{V}_2 = \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} & \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} & \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
$$

| First Header | Second Header |
| :----------- | ------------: |
| A**1**1      |         A*1*2 |
| A21          |           A22 |



You can create footnotes like this[^footnote].

[^footnote]: Here is the *text* of the **footnote**.

this [^1] note. [^n] note.

[^1]: This is my first footnote
[^n]: Visit http://example.com
[^n]: A final footnote



