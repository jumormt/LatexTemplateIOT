# Latex中文双栏显示论文，参考《北航学报模板》

## 模板文件说明
jbuaa.cls 模板文件

cite.sty、GB.cpx 引用样式、中文支持相关文件（文件内有原作者信息）

TempExample.tex 正文内容

TempExample.bib 参考文献

image 文件夹下是正文中用到的图片文件

## 使用说明
在完整安装texlive 2016 或者 texlive 2017条件下，直接在命令行按顺序运行如下命令即可
```sh
xelatex TempExample.tex
bibtex TempExample
xelatex TempExample.tex
xelatex TempExample.tex
```
最终生成TempExample.pdf文件

#######################################################

## 其他
Symbol 文件夹下是《变量符号说明》生成文档
增加了符号在文中的位置的信息，需要辅助文件TempExample.aux



