# AutoSidebarForDocsify

## 介绍
用课余时间写了一个Docsify 自动生成目录的插件。

## 功能
AutoSidebarForDocsify 主要功能为： Docsify 部署的博客自动生成目录。

## 环境要求
- nodejs

## 使用说明
将本项目的 autoSidebar.js 文件复制到 git项目根目录下。
**提醒**：使用前请注意备份好原有的 `_sidebar.md` 文件。运行程序将覆盖原文件。
```bash
$ node autoSidebar.js
```
完成后将在终端自动输出文档效果并写入到`_sidebar.md` 文件中

## 效果图
![](img/2021-03-12-12-42-08.png)

## 注意
已对目录进行优化，树状图不会出现重复路径。
