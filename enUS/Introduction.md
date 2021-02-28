---
aliases: []
favorited: true
created: 2020-03-26T12:45:15.481Z
modified: 2021-02-28T15:00:32.594Z
---
# 📝 Welcome to Crossnote

> It is recommended to view this notebook in [crossnote](https://crossnote.app/?repo=https%3A%2F%2Fgithub.com%2F0xGG%2Fwelcome-notebook.git&branch=master&filePath=README.md).

<!-- @crossnote.comment "id":"a53b8fc6-268d-405c-b65e-d2a4683ac277" -->

## 🔭 Introduction

**Crossnote** is a markdown notes reader & editor progressive web application that works offline ~~perfectly~~ (maybe not yet but soon 😂) and supports syncing with arbitrary git repository right inside your browser. It also supports opending and editing your local files.  

Crossnote is heavily inspired by [Markdown Preview Enhanced](https://github.com/shd101wyy/markdown-preview-enhanced), [Google Keep](https://keep.google.com), [Google Docs](https://docs.google.com), [Quip](https://quip.com), [Notion](https://www.notion.so), [GitBook](https://gitbook.com), [Notable](https://github.com/notable/notable), [Evernote](https://evernote.com/), [Bear](https://bear.app/), [RoamResearch](https://roamresearch.com/).

Unlike [Crossnote (_alpha_)](https://github.com/0xGG/crossnote/blob/master/README.alpha.md), which is completely cloud based, **Crossnote** aims to be offline first. That is, your data is stored entirely in your browser. We won't collect your notes and credentials to our server. **You own your data**.

The front-end of crossnote project is completely open sourced on GitHub [0xGG/crossnote](https://github.com/0xGG/crossnote). It is released under **AGPL3**. Any contributions or suggestions would be very helpful for the growth of the project.

You can easily synchronize your notebooks with arbitrary git repositories thanks to the awesome [isomorphic-git](https://github.com/isomorphic-git/isomorphic-git) project that makes running git possible right inside this web application. The wonderful [File System Access API](https://web.dev/file-system-access/) also makes it possible to open and edit your local files.

This application is still under development, and its production website is currently running on a Vultr VPS with only 8GB ram located in Los Angeles.

## 💾 Installation

On desktop computers and android devices, I would suggest you to try [crossnote](https://crossnote.app) on **Chrome**. You can also create `Shortcut` to add it to your home screen (`Menu (top right corner) -> More tools -> Create shortcut...`).

On iOS devices (iPhone and iPad), I would suggest you to try [crossnote](https://crossnote.app) on **Safari** and add the webpage to home screen. ([How to create website shortcuts on iPhone and iPad](https://www.igeeksblog.com/how-to-create-website-shortcuts-on-iphone-ipad/)).

> 🐞 However, the iOS will sometimes kill unactive background tasks, so running Crossnote in background sometimes has trouble. I haven't found any solutions...

## ⚗️ Functionalities

- 🤩 Write your favorite notes in markdown. See [basic markdown syntaxes](/demo/markdown.md).
- 📊 Different kinds of diagrams. See [the demo here](/demo/diagrams.md).
- ~~⌨️ Collaborative editing~~ This feature is supported in _alpha_ before but not in current _beta_ version. We will bring collaborative editing (probably in P2P way) back in the future.
- 🖼 Slides follows the same specs as in [Markdown Preview Enhanced](https://shd101wyy.github.io/markdown-preview-enhanced/#/presentation). See [the demo from MPE here](/demo/presentation.md)
- 🏷️Backlinks support.
 - 🕸️ Display the relationship of your notes in graph view.
  - 🗒️ Set up multiple aliases for your note.  For example [[../USA.md|USA]], [[../USA.md|United States]], [[../USA.md|美国]] all points to the same note.  
- 🖨️ Print your note to PDF. We are planning to support to export to more types of files in the future!
- 📤 Synchronize your notebook with arbitrary git repository. (🙋Please read the tutorial [here](/enUS/tutorial.md))
- 🛠 Widgets support that powers your markdown note. Type `/` for commands and play with the widgets.
  - `/timer`
  - Media
    - `/audio` [demo](/demo/audio.md)
    - `/video` [demo](/demo/video.md)
    - `/youtube` [demo](/demo/youtube.md)
    - `/bilibili` [demo](/demo/bilibili.md)
  - `/ocr`
  - `/kanban` (_beta_)
  - `/github_gist` [demo](/demo/github_gist.md)
    More widgets are coming out in the future.
- 📖 Set up Wiki by adding `SUMMARY.md` file.

## 🌤 Crossnote cloud widgets

Crossnote cloud widgets are the special type of widgets that interact with Crossnote cloud server (😂 Proudly running on a Vultr VPS with only 8GB ram located in Los Angeles).

The first cloud widget that we supported in Crossnote is the `/crossnote.comment` widget 💬. This widget allows you to insert a comment system in your markdown note. For example:

<!-- @crossnote.comment "id":"94f1c5da-7a18-41ea-8474-8f0d1bcc56a2" -->

You can create infinite number of cloud widgets during the _beta testing_ stage. But in the future, there will be a number limit for different types of user accounts.

## 🙋 Tutorial

We provide a short tutorial that guides you to create your first notebook with a git repository on GitHub [Here](/enUS/tutorial.md).

## 🕸️ Web Clipper

We haven't officially offered any web clipper support, but you could use the web clipper provided by Quiver to convert a webpage to markdown then copy it to Crossnote.

- [Quiver Web Clipper - Chrome Web Store](https://chrome.google.com/webstore/detail/quiver-web-clipper/hcnffmpopoelpggikahccdfenoobjigj)
- [Quiver Web Clipper - Firefox Add-on](https://addons.mozilla.org/en-US/firefox/addon/quiver-web-clipper/)

## 🌍 ~~Share you notebooks with the public~~
>👆 This feature is currently disabled

Yes you can publish your notebook to the public in `Explore` section.  
We currently only support publishing the notebook from a public repository on GitHub, GitLab, Gitea, or Gitea. We only collect README.md file data.  
Only the `README.md` data will be collected.

## 📅 Development plans

See the [Development Plans](https://github.com/0xGG/crossnote/projects/1).

## 📖 Development doc

Check [this](/development/README.md).

## 😀 Interested in this project?

The crossnote project is actually currently developed by only one developer [github/shd101wyy](https://github.com/shd101wyy). And I hope more people can join the force in the future.

The goal of this project is to help me **earn money**💰. Yes, reality is cruel 😣. My goal is to earn \$2000 USD with crossnote project by the end of 2020. As I am working as an indie developer, I need to making a living as well. I need income to help make this project alive, rent better servers, set up CDNs, etc.

My current plan is that all functionalities that can be done directly in browser will be free for sure, but those that have interactions with the backend server or have data to be stored in backend server will be charged.

If you are interested in this project and want to get more involved (or even help commercialize the project 😎), you can reach me either by my email `shd101wyy@gmail.com` (well I don't check my email very often), or by my wechat(微信) `shd101wyy`, or by my [Linkedin](https://www.linkedin.com/in/yiyi-wang-60416380/).

You can also join our discussion group on Wechat:

![](https://i.loli.net/2021/02/28/7nYsui2gcNyXOlo.jpg)  

Thank you!
