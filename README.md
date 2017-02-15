# XJTU-Thesis-Template
This is a LaTeX template for doctoral thesis of Xi`an Jiaotong University (XJTU). The platform is Windows + TexLive + XeLaTex.

本项目是西安交通大学博士学位论文 2014 版的 LaTeX 模板，这是一个初步版本，有问题请大家反馈给我（西安交通大学-电子科学与技术-张明，zmjerry@163.com）。

本模板在 Windows + TexLive2016 + Texsdudio 平台下开发，采用 XeLaTex 编译。虽然之前也开发过一个基于 CTeX 的模板，但是经过多方面比较后发现 TexLive+XeLaTex 处理中文更好，多以旧的模板没有共享。

模板使用非常简单，修改封面 (setup/cover.tex)、摘要 (setup/abstract.tex)、 正文章节 (body 文件夹) 以及附录章节 (appendix 文件夹) 中的相关内容即可。

本模板同时共享在了 Overleaf 平台：https://www.overleaf.com/latex/templates/latex-template-for-doctoral-thesis-of-xjtu/bmrqcdhbdrcw
Overleaf 平台没有 Windows 系统字体，所以上传了宋体 (SimSun.ttf) 和黑体 (SimHei.ttf) 字体文件，同时 package.tex 文件中的字体设置命令加了 .ttf 后缀：
\setCJKmainfont{SimSun.ttf}
\setCJKsansfont{SimHei.ttf}
\setCJKfamilyfont{hei}{SimHei.ttf}
（本站共享的是 Windows 系统下的模板，字体设置命令不带 .ttf 后缀。）
