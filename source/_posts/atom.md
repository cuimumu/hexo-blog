---
title: atom windows 常用快捷键
---


## 【Tree View】目录树操作
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
`m` 移动目录

`ctrl-k k` 或者 `cmd-k up` 在上半视图中打开文件  
`ctrl-k j` 或者 `cmd-k down` 在下半视图中打开文件  
`ctrl-k h` 或者 `cmd-k left` 在左半视图中打开文件  
`ctrl-k l` 或者 `cmd-k right` 在右半视图中打开文件  

`ctrl-n` tree-view:open-selected-entry-in-pane-n  
`ctrl-shift-C` 复制当前文件绝对路径

## 【Pane】视图窗口操作

`ctrl-k ctrl-up` 上半视图获得焦点  
`ctrl-k ctrl-down` 下半视图获得焦点  
`ctrl-k ctrl-left` 左半视图获得焦点  
`ctrl-k ctrl-right` 右半视图获得焦点  
`ctrl-k ctrl-p` 前一个视图获得焦点  
`ctrl-k ctrl-n` 后一个视图获得焦点  

`alt-n` 切换到当前Pane第n个TAB页  
`ctrl-w` 关闭当前TAB页  
`ctrl-shift-w` 关闭所有Pane退出编辑器  
`ctrl-k ctrl-alt-w` 关闭当前TAB之前的其他页面  
`ctrl-shift-t` 重新打开之前关闭的TAB  
`ctrl-shift-tab` 显示前一个曾经用过的TAB  
`ctrl-tab` 显示后一个曾经用过的TAB  
`ctrl-pageup` pane:show-previous-item  
`ctrl-pagedown` pane:show-next-item  

## 【File】文件操作
`ctrl-shift-s`  保存所有打开的文件  
`ctrl-shift-o`  打开目录  
`ctrl-t`或`cmd-p` 查找文件  
`ctrl-b` 在打开的文件之间切换  
`ctrl-shift-b` 只搜索从上次git commit后修改或者新增的文件  


## 【Editor】编辑文本
### 基本操作
`ctrl-j` 将下一行与当前行合并  
`ctrl-up` 使当前行向上  
`ctrl-down` 使当前行向下移动  
`ctrl-shift-d` 复制当前行到下一行  
`ctrl-shift-k` 删除当前行  
`ctrl-k ctrl-u` 使当前字符大写  
`ctrl-k ctrl-l` 使当前字符小写  

### 删除和剪切
`ctrl-shift-K` 删除当前行  
`ctrl-backspace` 删除到当前行开始  
`ctrl-K` 剪切到当前行结束  
`alt-backspace` 或 `alt-H` 删除到当前单词开始  
`alt-delete` 或 `alt-D` 删除到当前单词结束  

### 多光标和多处选取  
`ctrl-click` 增加新光标   
`ctrl-alt-up` editor:add-selection-above  
`ctrl-alt-down` editor:add-selection-below  
`alt-shift-left` editor:move-selection-left  
`alt-shift-right` editor:move-selection-right  
`ctrl-d` 选取文档中和当前单词相同的下一处  

### 编码方式  
`ctrl-shift-u` 调出切换编码选项  

## 【Find & Replace】查找和替换  
`ctrl-f` 在buffer中查找  
`ctrl-shift-f` 在整个工程中查找  


## 【Flod & UnFlod】折叠展开代码块  
`ctrl-alt-[`	editor:fold-current-row  
`ctrl-alt-]`	editor:unfold-current-row  
`ctrl-alt-{`	editor:fold-all  
`ctrl-alt-}`	editor:unfold-all  

`ctrl-k ctrl-0`	editor:unfold-all  
`ctrl-k ctrl-n`	editor:fold-at-indent-level-n (n=1-9)  


## 【Grammar】文件语法类型
`ctrl-shift-L` 选择文件语法类型  

## 【Zoom Font】调整字体大小  

> 可在文本编辑窗口、图片预览、markdown预览中使用

`ctrl-+` 增大字体  
`ctrl--` 减小字体  
`ctrl-0` 还原字体  

## 【GO TO LINE】 行跳转
`ctrl-g`  跳转到指定行数

## 【Bracket Matcher】 括弧匹配  
`ctrl-m`	bracket-matcher:go-to-matching-bracket  
`ctrl-alt-backspace`	bracket-matcher:remove-matching-brackets  
`ctrl-alt-,` bracket-matcher:select-inside-bracketsto  
`ctrl-alt-.` bracket-matcher:close-tag to close the current XML/HTML tag.

## 【Tools】切换开发工具  
`ctrl-shift-i` 切换出开发工具

## 【Markdown】预览
`ctrl-shift-M` Markdown预览  
