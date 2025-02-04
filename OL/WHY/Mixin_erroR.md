---
title: 为什么会出现Mixin（注入）错误
---

# 为什么会出现Mixin（注入）错误

![MixinError](../imgs/mixin_error.png)  
Mixin错误是一种在Architectury架构的模组中十分常见的崩溃原因。它主要是因为Architectury架构的模组中每个加载器使用Architectury自动生成的refmap，若refmap错误就会导致游戏崩溃。  
遇到此类问题可以到我们GitHub仓库的Issues中的[Mixin问题合集Issue](https://github.com/StarCarefree/OpenLink/issues/82)中进行反馈。  
![MixinGitHubIssue](../imgs/mixin_githubissue.png)

## 在Issue进行评论反馈Mixin错误

1. 打开GitHub仓库的Issues中的[Mixin问题合集Issue](https://github.com/StarCarefree/OpenLink/issues/82)。
2. 在Issue下方提交您的报错并上传您的日志文件（关于如何获取日志文件，参见[如何分析日志](../HowTo/LogAnalysis)）。格式为：
`[游戏版本/Game version]-[加载器及版本/Loader and version]`并在后面附上您的日志文件。
3. 若我们回复了您的评论，代表您的Mixin错误已经被我们知晓，我们将在下一个版本中修复该Mixin错误。
