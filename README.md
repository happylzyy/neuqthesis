NEUQ 本科毕业设计论文 LaTex 模板

=============================

[东北大学秦皇岛分校](http://www.neuq.edu.cn/) 2020年本科毕业论文 [LaTex](https://www.latex-project.org/) 模板，根据2020年毕设doc文档格式修改而来。

原始模板[PaperLatexTemplate](https://github.com/techflowing/PaperLaTexTemplate)来自一位学长 `coffin`，在完成毕业论文的过程中，深刻体验到 LaTex 排版的干净整洁，以及修改格式的方便快捷，特此分享出来。

初次修改，可能还存在不符合毕设要求的地方，欢迎提出意见和改进建议。

<!-- more -->

#### LaTeX概览
> 摘自维基百科

LaTeX， 是一种基于TEX的排版系统，由美国电脑学家莱斯利·兰伯特在20世纪80年代初期开发，利用这种格式，即使用户没有排版和程序设计的知识也可以充分发挥由TEX所提供的强大功能，能在几天，甚至几小时内生成很多具有书籍质量的印刷品。对于生成复杂表格和数学公式，这一点表现得尤为突出。因此它非常适用于生成高印刷质量的科技和数学类文档。这个系统同样适用于生成从简单的信件到完整书籍的所有其他种类的文档。

简单点说：LaTeX 基于 TeX，主要目的是为了方便排版。在学术界的论文，尤其是数学、计算机等学科论文都是由 LaTeX 编写, 因为用它写数学公式非常漂亮。

#### 项目结构

* `images/`，存放论文中引用的图片资源,包括论文封面
* `other/`，存放一些其它资源，比如图标源文件等
* `sections/`，存放论文每一章的LaTex源文件
* `citation.bib`，论文引用文献数据
* `main.tex`，项目主文件
* `main.pdf`，输出的 PDF 文件

#### LaTex环境

> 基于 Windows10 系统，其它系统请自行寻找编辑器，配置环境

编辑器：[Visual Studio Code](https://code.visualstudio.com/)

Tex发行版：[CTex](http://www.ctex.org/HomePage)

#### 参考资料

- [CTex宏包说明](http://mirrors.ibiblio.org/CTAN/language/chinese/ctex/ctex.pdf)
- [Natural Sciences Citations and
  References](http://mirrors.ctan.org/macros/latex/contrib/natbib/natbib.pdf)
- [The tocloft package](http://www.ctex.org/documents/packages/contents/tocloft.pdf)
- [titlesec 与titletoc 宏包使用说明](http://static.latexstudio.net/wp-content/uploads/2016/12/titlesec_c.pdf)
- [The titlesec titletoc Packages](http://www.ctex.org/documents/packages/layout/titlesec.pdf)
- [在 LaTeX 中使用微分算子的正确姿势 | 始终](https://liam.page/2017/05/01/the-correct-way-to-use-differential-operator/)
- [在 LaTeX 的 book 类中实现章节间空白页「This page is intetionally left blank」的效果](https://liam.page/2015/07/03/cleardoublepage-this-page-is-intentionally-left-blank/)

