---
note:
    createdAt: 2020-03-26T13:04:29.042Z
    modifiedAt: 2020-03-26T15:10:05.313Z
    tags: [introduction]
    id: ""
---
# 📝 欢迎使用交叉笔记 (beta)

## 🔭 Introduction

**Crossnote 交叉笔记** 可能是这个世界上第一款可离线工作并且支持在浏览器中直接与 git 仓库进行同步的的 markdown 笔记阅读器 & 编辑器。

交叉笔记受到了这些产品的启发： [Markdown Preview Enhanced](https://github.com/shd101wyy/markdown-preview-enhanced)，[Google Keep](https://keep.google.com)，[Google Docs](https://docs.google.com)，[Quip](https://quip.com)，[Notion](https://www.notion.so)，[Notable](https://github.com/notable/notable)，[Evernote](https://evernote.com/)，以及 [Bear](https://bear.app/)。

不像 [交叉笔记 (*alpha*)](https://raw.githubusercontent.com/0xGG/crossnote/master/README.alpha.md)这款完全基于云端的笔记软件，**交叉笔记 (beta)** 的目标是离线第一。你的所有数据将会保存于你的浏览器中。我们不会上传你的笔记和密钥到我们的服务器。**你拥有的你的数据的控制权**。

交叉笔记项目的前端是完全在 GitHub 上开源的 [0xGG/crossnote](https://github.com/0xGG/crossnote)。它使用的是 **AGPL3** 协议。任何的代码贡献或者项目建议都会对这个项目的发展产生很大的助力。  

你可以非常方便地将你的笔记本和任意的 git 仓库进行同步。这点归功于一个炫酷的项目 [isomorphis-git](https://github.com/isomorphic-git/isomorphic-git)。它使得直接在浏览器中运行 git 命令成为了可能。

交叉笔记项目目前还在开发中，并且它的生产环境只部署于位于洛杉矶的一个只有 8GB 内存的 Vultr 主机上。

## 💾 安装

在电脑端或者安卓设备，我们推荐你用 **Chrome** 打开 [交叉笔记](https://crossnote.app)。你可以通过点击右上角的菜单，选择 `更多工具`，然后选择 `添加到桌面` 进行安装。

在 iOS 设备（iPhone 和 iPad）上，我建议用 **Safari** 打开 [交叉笔记](https://crossnote.app)。然后点击底部的分享按钮，选择 `添加到主屏幕` 进行安装。  

## ⚗️ 功能
- 🤩 用 markdown 编写你最喜爱的笔记。查看 [markdown 的基本语法](/demo/markdown.md).   
- 📊 各种各样的图表支持. 查看 [演示](/demo/diagrams.md). 
- ~~⌨️ 协同编辑~~ 这个功能原来在 *alpha* 版本中是支持的，但是当前的 *beta* 版本取消了支持。我们未来会把这个功能加回来（可能用 P2P 的实现方式）。
- 🖼 和 [Markdown Preview Enhanced](https://shd101wyy.github.io/markdown-preview-enhanced/#/presentation) 中相同标准的幻灯片制作。查看 [MPE 中的演示](/demo/presentation.md)
- 🏷️ 无限嵌入式标签。（没错我们喜欢 [Bear](https://bear.app) 和 [Notable](https://github.com/notable/notable) 的设计思路）
- 🔐 内置 AES 算法加密，支持你设置密码保护你的笔记。   
- 🖨️ 打印你的笔记为 PDF。我们在未来会支持更多的导出格式！
- 📤 同步你的笔记本与 git 仓库 （详尽的教程还在编写中 🚌）
 - 🛠 让你的笔记更加强健有力的挂件。输入 `/` 来显示命令并且尝试创建些你的挂件。
   - `/timer` 
   - Media
     - `/audio`
     - `/video`
     - `/youtube`
     - `/bilibili`
     - `/netease`
   - `/ocr`
   - `/kanban` (*beta*)
   - `/abc`
    更多的挂件会在未来支持。  
  - 📖 通过添加 `SUMMARY.md` 开设置维基。    
    
## 📅 开发计划
查看 [Development Plans](/development/plans.md).  

## 📖 开发文档
TODO

## 😀 Interested in this project?
The crossnote project is actually currently developed by only one developer [github/shd101wyy](https://github.com/shd101wyy). And I hope more people can join the force in the future.

The goal of this project is to help me **earn money**💰. Yes, that is the cruel reality. My goal is to earn $2000 USD with crossnote project by the end of 2020. As I am working as an indie developer, I need to making a living as well. I need income to help make this project alive, rent better servers, set up CDNs, etc. 

My current plan is that all features that can be done directly in browser will be free for sure, but those that have interactions with the backend server or have data to be stored in backend server will be charged.

If you are interested in this project and want to get more involved (or even help commercialize the project 😎), you can reach me either by my email `shd101wyy@gmail.com` (well I don't check my email very often), or by my wechat(微信) `shd101wyy`, or by my [linkedin](https://www.linkedin.com/in/yiyi-wang-60416380/).

Thank you!






