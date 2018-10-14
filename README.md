# learn-m4

## 本仓库内容

* GNU m4学习笔记

```
Something I hope you know before go into the coding~
First, please watch or star this repo, I'll be more happy if you follow me.
Bug report, questions and discussion are welcome, you can post an issue or pull a request.
```
## 什么是宏

* 书名是『宏』，它被作者展开为这本书的全部内容。
* 药瓶上的标签是『宏』，将药片从瓶中倾倒出来，就是这个宏的展开结果。
* 被用的最多的『宏』，应该是 Internet 的超级链接。
* 每当你点击一个超级链接，就相当于将这个宏展开为网页中的内容。
* 生活中，类似的例子还有很多，只要你给某种具体的事物贴上了一个标签，那么这个标签就相当于宏。


## 宏的诞生

C 语言自诞生后，只用了 5 年就让汇编语言归隐山林了，这可能要归功于 Unix 的成功以及 Dennis Ritchie 的忽悠。Steve Johnson——yacc, lint, spell 以及 PCC（Portable C Compiler）的作者说：**『Dennis Ritchie 告诉所有人，C 函数的调用开销真的很小很小。于是人人都开始编写小函数，搞模块化。然而几年后，我们发现在 PDF-11 中函数的调用开销依然非常大，而 VAX 机器上的代码往往在 CALL 指令上花费掉 50% 的运行时间。Dennis 对我们撒了谎！但为时已晚，我们已经欲罢不能……』**

现代的编程语言，几乎都赞同用函数来取代宏。拥护者们往往会给出一些冠冕堂皇的理由是，诸如不必额外实现一个宏处理器，函数比宏更安全并且更容易调试。事实上，他们的理由仅仅是迎合现实而已。如果将这些人扔进时空裂缝让他们穿越到 Ken Thompson 编写 Unix 系统的时代，让他们也在一台废弃的 PDP-7 型号的计算机上写程序。在这种内存只有 8KB 的计算机上，那些冠冕堂皇的理由近乎与科幻小说等价。**函数之所以能够取代宏，仅仅是因为 CPU 的计算速度比过去更快了，内存比以前更大了，牺牲一些程序性能，让编程工作更容易一些，这样比较合算而已。编程语言的性能与机器的性能似乎总是成反比的。**

宏被很多人主观的弃用了，得益于现代编程语言的表达能力，他们似乎几乎不需要用宏，于是他们作出结论：宏过时了。**事实上，宏会永远居于众编程语言之上的，因为前者总是能够生成后者。**编程专家总是会告诉我们，要慎用宏。胆子小的程序猿看到宏就躲得远远的，以至于他们总觉得那些使用宏的代码是糟糕的，是不安全的。事实上，在编程中，若能恰如其分的使用宏，可以让代码更加简洁易读，特别是对 C 语言这种表现力不足的语言。


## m4简介

```
GNU M4 is an implementation of the traditional Unix macro processor.
It is mostly SVR4 compatible although it has some extensions (for example, handling more than 9 positional parameters to macros).
GNU M4 also has built-in functions for including files, running shell commands, doing arithmetic, etc.

GNU M4 is a macro processor in the sense that it copies its input to the output expanding macros as it goes.
Macros are either builtin or user-defined and can take any number of arguments.
Besides just doing macro expansion, m4 has builtin functions for including named files, running UNIX commands, doing integer arithmetic, manipulating text in various ways, recursion etc... m4 can be used either as a front-end to a compiler or as a macro processor in its own right.

One of the biggest users of GNU M4 is the GNU Autoconf project.
```


## 相关站点

* GNU m4总站:<https://www.gnu.org/software/m4/m4.html>
* GNU m4 Ftp站点:<http://ftp.gnu.org/pub/gnu/m4/>

## 目录


## 参考书籍



## 思维导图



## 参考博客

* 让这世界再多一份GNU m4 教程:<https://blog.csdn.net/Timekeeperl/article/details/50738164>
* 宏定义的黑魔法 - 宏菜鸟起飞手册:<https://onevcat.com/2014/01/black-magic-in-macro/>



## 总结
