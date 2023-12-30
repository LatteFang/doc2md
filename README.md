# doc2md
docx文件转换md文件的小工具-源代码模式

转换思路
Word文档到Markdown文档的转换通常我们是分两步来实现:
Step1 Word文档转换为HTML文档
Step2 HTML文档转换为Markdown文档

依赖模块
mammoth：用于将Word文档转换为HTML文档的模块
markdownify：用于将HTML文档转换为Markdown文档的模块

依赖包安装：（清华镜像源）
pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple/
