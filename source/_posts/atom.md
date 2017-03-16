---
title: atom 使用
---


## 目录树操作
`alt-\` 光标焦点在目录树和视图窗口间切换  
`ctrl-\` 显示(隐藏)目录树  
`ctrl-[` 和 `ctrl-]` 展开(隐藏)当前目录  
`ctrl-al-]` 和 `ctrl-al-[` 展开(隐藏)所有目录  
`right` 和 `left`  展开(隐藏)当前目录  
`alt-right` 和 `alt-left`  展开(隐藏)所有目录  

`a` 添加文件  
`shift-a` 添加文件夹  
`d` 复制当前文件(duplicate)  
`i` 显示(隐藏)版本控制忽略的文件  

`k` 向上移动  
`j` 向下移动  
`h` 向左折叠  
`l` 向右展开  

`ctrl-k k` 或者 `cmd-k up` 在上半视图中打开文件
`ctrl-k j` 或者 `cmd-k down` 在下半视图中打开文件  
`ctrl-k h` 或者 `cmd-k left` 在左半视图中打开文件
`ctrl-k l` 或者 `cmd-k right` 在右半视图中打开文件  

`ctrl-shift-C` 复制当前文件绝对路径

## 视图窗口操作

`ctrl-k ctrl-up` 上半视图获得焦点
`ctrl-k ctrl-down` 下半视图获得焦点
`ctrl-k ctrl-left` 左半视图获得焦点
`ctrl-k ctrl-right` 右半视图获得焦点
`ctrl-k ctrl-p` 前一个视图获得焦点
`ctrl-k ctrl-n` 后一个视图获得焦点

`alt-n` 切换到第n个TAB页



## Markdown预览
`ctrl-shift-M` Markdown预览  

## 文件切换
`ctrl-shift-s`  保存所有打开的文件  
`ctrl-shift-o`  打开目录  
`ctrl-t`或`cmd-p` 查找文件  
`ctrl-b` 在打开的文件之间切换  
`ctrl-shift-b` 只搜索从上次git commit后修改或者新增的文件  


## 选取
> 大部分和导航一致，只不过加上shift  

`ctrl-shift-P`  选取至上一行  
`ctrl-shift-N`  选取至下一样  
`ctrl-shift-B`  选取至前一个字符  
`ctrl-shift-F`  选取至后一个字符  
`alt-shift-B`, `alt-shift-left`  选取至字符开始  
`alt-shift-F`, `alt-shift-right`  选取至字符结束  
`ctrl-shift-E`, `cmd-shift-right`  选取至本行结束  
`ctrl-shift-A`, `cmd-shift-left`  选取至本行开始  
`cmd-shift-up`  选取至文件开始  
`cmd-shift-down`  选取至文件结尾  
`cmd-A`  全选  
`cmd-L`  选取一行，继续按回选取下一行  
`ctrl-shift-W`  选取当前单词  

## 编辑和删除文本
### 基本操作
`ctrl-T` 使光标前后字符交换  
`cmd-J` 将下一行与当前行合并  
`ctrl-cmd-up`, `ctrl-cmd-down` 使当前行向上或者向下移动  
`cmd-shift-D` 复制当前行到下一行  
`cmd-K`, `cmd-U` 使当前字符大写  
`cmd-K`, `cmd-L` 使当前字符小写  
`cmd-shift-P` 搜索命令  

### 删除和剪切
`ctrl-shift-K` 删除当前行  
`cmd-backspace` 删除到当前行开始  
`cmd-fn-backspace` 删除到当前行结束  
`ctrl-K` 剪切到当前行结束  
`alt-backspace` 或 `alt-H` 删除到当前单词开始  
`alt-delete` 或 `alt-D` 删除到当前单词结束  

### 多光标和多处选取  
`cmd-click` 增加新光标  
`cmd-shift-L` 将多行选取改为多行光标  
`ctrl-shift-up`, `ctrl-shift-down` 增加上（下）一行光标  
`cmd-D` 选取文档中和当前单词相同的下一处  
`ctrl-cmd-G` 选取文档中所有和当前光标单词相同的位置  

### 括号跳转  
`ctrl-m` 相应括号之间，html tag之间等跳转  
`ctrl-cmd-m` 括号(tag)之间文本选取  
`alt-cmd-.` 关闭当前XML/HTML tag  

### 编码方式  
`ctrl-shift-u` 调出切换编码选项  

## 查找和替换  
`ctrl-f` 在buffer中查找  
`ctrl-shift-f` 在整个工程中查找  


## 折叠  
`alt-cmd-[` 折叠  
`alt-cmd-]` 展开  
`alt-cmd-shift-{` 折叠全部  
`alt-cmd-shift-}` 展开全部  
`cmd-k cmd-N` 指定折叠层级 N为层级数  

## 文件语法高亮  
`ctrl-shift-L` 选择文本类型  
