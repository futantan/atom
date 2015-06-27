## 文件切换
`ctrl-shift-s`  保存所有打开的文件  
`cmd-shift-o`  打开目录  
`cmd-\`   显示或隐藏目录树  
`ctrl-0`   焦点移到目录树  
目录树下，使用a，m，delete来增加，修改和删除  
`cmd-t`或`cmd-p` 查找文件  
`cmd-b` 在打开的文件之间切换  
`cmd-shift-b` 只搜索从上次git commit后修改或者新增的文件  

## 导航  
（等价于上下左右）  
`ctrl-p` 前一行  
`ctrl-n` 后一行  
`ctrl-f` 前一个字符  
`ctrl-b` 后一个字符  

`alt-B`, `alt-left` 移动到单词开始  
`alt-F`, `alt-right` 移动到单词末尾  

`cmd-right`, `ctrl-E` 移动到一行结束  
`cmd-left`, `ctrl-A`  移动到一行开始  

`cmd-up` 移动到文件开始  
`cmd-down` 移动到文件结束  

`ctrl-g` 移动到指定行 row:column 处

`cmd-r` 在方法之间跳转

## 书签
`cmd-F2` 在本行增加书签  
`F2` 跳到当前文件的下一条书签  
`shift-F2` 跳到当前文件的上一条书签  
`ctrl-F2` 列出当前工程所有书签  

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
`ctrl-shift-U` 调出切换编码选项  

## 查找和替换  
`cmd-F` 在buffer中查找  
`cmd-shift-f` 在整个工程中查找  

## 代码片段  
`alt-shift-S` 查看当前可用代码片段  
> 在`~/.atom`目录下`snippets.cson`文件中存放了你定制的snippets  

[定制说明](https://atom.io/docs/v1.0.0/using-atom-snippets)  

## 自动补全  
`ctrl-space` 提示补全信息  

## 折叠  
`alt-cmd-[` 折叠  
`alt-cmd-]` 展开  
`alt-cmd-shift-{` 折叠全部  
`alt-cmd-shift-}` 展开全部  
`cmd-k cmd-N` 指定折叠层级 N为层级数  

## 文件语法高亮  
`ctrl-shift-L` 选择文本类型  

## 使用Atom进行写作  
`ctrl-shift-M` Markdown预览  
可用代码片段
> b, legal, img, l, i, code, t, table
