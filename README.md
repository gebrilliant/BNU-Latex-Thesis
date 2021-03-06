# 北师大本硕博学位论文Latex模版——Mac版
感谢北师大天文系余恒老师的模版，由于之前的模版只是针对Windows，本人针对Mac用户，做了简单的更改，希望所有Mac用户能方便的写作。

*使用方式：下载压缩文件，仔细阅读说明文件，解压即可使用。
使用特别注意:Mac用户编译latex需要下载TexLive的 Mac版本——MacTex，但是新版本（2019）的 MacTex与此模板存在兼容问题。

解决方法:  

1、安装mactex-20140525.pkg。这个版本可以在6维空间快速下载。如需帮助请看4；  
2、解压BnuThesis文件，打开main.tex, 选择XeLaTeX模式排版编译；  
3、Mac用户强烈建议使用TexPad编辑器（付费软件）进行编译，用户界面友好，使用前请下载相关宏包，建议下载除去小语种宏包之外的所有宏包。关于TexPad的使用请Google；   
4、获取 MacTex—20140525文件包+TexPad破解安装包下载链接（建议支持正版）链接：https://pan.baidu.com/s/1lhDTsz3Gi5RwHpkxrUwc5Q 
提取码：ze0o；  
5、北师大的同学在使用过程中遇到自己无法解决的问题可以私信我（bwtong@mail.bnu.edu.cn）时间宽裕可答疑解惑，也可提供百度云超级会员账号快速下载文件；  
6、本科生毕业模版请参考 https://github.com/jinyiliu/bnu-bachelor-thesis。
 
以下说明 搬运自 http://gerry.lamost.org/blog/?p=811 此链接可快速找到适用于Windows的模版

对于许多理工科学生来说，用Word写论文并不是一件愉快的事情。但如果没有现成的模板，Latex也不是那么平易近人。之前Gsoul ,WX 硕士毕业时参考清华北大的论文模板自行修改，发布了北师大的第一个Latex学位论文模板。不过当时清华模板的结构代码还不够规范，加上学校的论文格式要求也有了些变化，我便根据最新的清华大学论文模板 Thuthesis 4.5.1 UTF版重新改了一个出来。 硕士博士部分与2010年研究生院公布的《学位论文编写规范》和相应Word模板基本吻合。本科论文部分因为尚未看到严格的规定就没有仔细核对，基本与硕博论文的格式保持一致。生成的文件可顺利通过学校图书馆的学位论文系统提交。

BnuThesis 是北京师范大学学位论文 LaTeX 模板。在清华大学论文Latex模板ThuThesis的基础上修改而来。支持学士、硕士、博士论文格式。模板主要包括 bnuthesis.cls, bnuthesis.cfg, bnubib.bst 三个风格文件。其中cls定义格式代码，cfg 规范名称表达，bst 指定参考文献引用格式。帮助和说明文件仍沿用清华的版本。用户编辑的内容包括：

main.tex 主控文档，可通过 onlyinclude 选项单独编译选定章节，加快文件生成速度。
data/ 文档目录，论文的文字部分都放在这里
ref/ 参考文献目录，通常只需要 bib 文件
figures/ 图片目录
标准编译过程是 latex – bibtex – latex – latex – dvips – ps2pdf （这时图片应为eps格式，或加载 epstopdf 宏包）。也可以使用 pdflatex/xelatex 等 。在 liangzi@ustc 制作的 TeXLive2009 上测试完成。注意所有文本文件都需要保存为UTF8编码格式，否则编译无法通过。
北师大论文封面

目前尚未解决的问题包括：
1、封面可能不够标准，不过研究生院会直接提供；
2、保密标签不知道具体格式，没有处理。
