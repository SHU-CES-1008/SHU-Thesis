## 关于

此宏包旨在建立一个简单易用的上海大学硕士学位论文 LaTeX 模板

## 使用

- 安装LaTex，参考如下教程（当然也可以参考其他）
  - MacOS：https://zhuanlan.zhihu.com/p/102823687
  - Windows：https://miktex.org/download

- 配合VSCode使用
- 上述安装过程中需要在VSCode中安装`LaTeX Workshop`和`LaTeX Utilities`两个插件
- 手动修改`cover.docx`，并生成`cover.pdf`
- 根据`cover.pdf`页数在`shu-thesis.tex`中修改117行和119行`\includepdf[pages={1-x}]{cover.pdf}`和`\setcounter{page}{x}`，`x`为`cover.pdf`的实际页数（手动修改）
- 除了`.bib`和`.tex`外都是编译过程中生成的中间文件，如果使用过程中需要手动删除需注意不要误删
- 第一次编译正文时需要在正文中引用一篇参考文献，否则会报`I couldn't open file name 'shu-thesis.aux'`的问题

## 祝各位顺利毕业