---
tags:
  - tutorial
created: 2020-03-28T08:22:40.925Z
modified: 2020-03-28T08:37:34.003Z
---

# 教程

> 这个教程假设你的笔记本是保存在一个 GitHub 上的仓库中的。
> 理论上来讲，所有的 git 仓库都使用方法都一样，例如 GitLab，码云，或者你自己搭建的等。

1. **创建一个不是空的 git 仓库**

如果你已经拥有了一个 git 仓库，你可以直接跳到下一步。
否则，你可以查看这个官方的 [GitHub 教程](https://help.github.com/en/github/getting-started-with-github/create-a-repo)来学习如何创建一个 git 仓库。

例如，下面我创建了一个名字叫做 `notebook-demo` 的 git 仓库。

![](https://i.loli.net/2020/03/28/nuEUtBbsKl8pIZS.png)

2. **添加你的笔记本到交叉笔记**

点击侧边栏**笔记本**旁的 `+` 按钮。

然后输入我们刚刚创建的仓库的 git 链接。例如：
`https://github.com/shd101wyy/notebook-demo.git`

![](https://i.loli.net/2020/03/28/7v9k4STNX81r3OW.png)

点击 **添加** 按钮来添加一个笔记本。

> 如果你在从一个私有的仓库下载一个笔记本，你可能需要填写 `用户名` 和 `密码` 栏。别担心，我们不会上传你的密钥到我们的服务器。
>
> 你也可以随后在笔记本设置中设置你的仓库。

3. **让你的笔记本保持最新**

交叉笔记当前还不支持自动更新笔记本。  
你需要手动上传你的笔记本到 git 仓库或者从 git 仓库下载更新。

在编辑器上方的工具栏中有两个按钮可以帮你实现这个任务。

![](https://i.loli.net/2020/03/28/UPgbTWtAsnDHurd.png)

在你上传一个笔记本的时候，你需要填写你的 `（git 仓库）用户名` 和 `（git 仓库）密码`。

对于一个 GitHub 上的笔记本，我们建议你在 `用户名` 栏（不是 `密码` 栏）填写 `Personal Access Token`。查看这个 [GitHub 教程](https://help.github.com/en/github/authenticating-to-github/creating-a-personal-access-token-for-the-command-line) 来学习如何创建 personal access token，并且请注意我们只需要 `repo` 权限。

例如：

![](https://i.loli.net/2020/03/28/i43xKVZEQwptc56.png)

如果你有任何关于这个教程的问题，请随时在 GitHub 上发个 [Issue](https://github.com/0xGG/crossnote/issues)😉。
