# Mostly-Harmless-Resume-Template
# 基本无害的简历模板
Mostly Harmless Resume Template
Copyright 2022  Qiu Renxiang
2022/12/09 alpha

本模板在https://github.com/sb2nov/resume
基础上进行改进，主要变化有：
1. 出于个人审美，对布局、文字和段落之间的间距进行部分修改
2. 对部分功能的逻辑进行修改，如文档类、页边距、heading的表达逻辑（原模板采用表格命令实现，若字数较多，会出现不同段落文字无法重叠的问题）等，增加易用性和稳健性。

使用示例：

    \section{Professional Experience}
    \resumeHeading{项目名称}{地点}{角色}{时间}
    \resumeItemListStart
    \resumeItemWithoutTitle{内容一}
    \resumeItemWithoutTitle{内容二}
    \resumeItemListEnd

    \resumeHeading{项目名称}{地点}{角色}{时间}
    \resumeItemListStart
    \resumeItem{小标题一：}{内容一}
    \resumeItemW{小标题二：}{内容二}
    \resumeItemListEnd

如果你有任何建议和疑问请发送邮件至,协助我做的更好。
重要提示：
  1. 请确保使用 UTF-8 编码保存
  2. 请使用 pdfLaTeX编译
  3. 修改、使用、发布本文档请务必遵循 LaTeX Project Public License
  4. 不需要的注释可以尽情删除
