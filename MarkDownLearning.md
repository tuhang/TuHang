# MarkDown学习笔记

- [MarkDown学习笔记](#markdown学习笔记)
  - [粗体、斜体、删除线、表情](#粗体斜体删除线表情)
  - [有序列表、无序列表](#有序列表无序列表)
  - [test](#test)
  - [复选框](#复选框)
  - [表格](#表格)
  - [链接](#链接)
  - [添加代码](#添加代码)
  - [引用](#引用)
- [技巧建议](#技巧建议)
- [本文的 md 源码](#本文的-md-源码)

## 粗体、斜体、删除线、表情
**粗体**    
*斜体*     
~~删除线~~     
:smile:     
建议使用VsCode的插件

## 有序列表、无序列表
- 第一级
  - 第二级
    - 第三级    

1. 第一项
2. 第二项
3. 第三项

## test

## 复选框
- [x] 选项一
  - [ ] 选项二

## 表格

 | 水果 | 价格 | 数量  |
 | :---: | :---: | :---: |
 | 香蕉 |   $1 |   5   |
 | 苹果 |   $1 |   6   |
 | 草莓 |   $1 |   7   |

> `:` 的位置决定了对齐的位置，`:--`左对齐,`--:`右对齐

## 链接
- this is a [a link](www.g.cn)
- [锚点](##表格)
- g.cn

## 添加代码
    package main
    import "fmt"
    func main() {
	    var word = "hello world"
	    fmt.Println(word)
    }

这里有一行 `内部的代码（也可以用来强调）`   
还有 `Hello world`  

## 引用
> TIP ：Shell命令可以用 `\`来换行  
> **转义符的应用 :** 
> 1. \*   
> 2. \\
> 
> **规范：** 每一行都加上`>`

---    

# 技巧建议
1. 提高效率，使用VScode的插件 ：[Markdown All in One ](https://github.com/yzhang-gh/vscode-markdown)
   1. 建立TOC目录：CTRL+SHIFT+P  -> CTOC
   2. 更新TOC目录：CTRL+SHIFT+P  -> UTOC
2. [中文文案排版指北](https://github.com/sparanoid/chinese-copywriting-guidelines)

# 本文的 `md` 源码
