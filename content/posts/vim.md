---
title: 'Vim'
date: 2021-06-10
---

## 简介

vim 是一款强大、高度可定制的文本编辑工具。

## 工作模式

vim 支持多种工作模式：

- 普通模式
- 插入模式
  - 'i' 光标插入
  - 'a' 光标后插入
  - 'o' 换行插入
- 命令航模式
- 可视化模式
  - 'v' 字符
  - 'V' 行
  - 'ctrl' + 'v' 块 
- 替换模式 (`R`)

各个模式按 'esc' 切换为普通模式。

## 基本操作

### 光标移动

### 可视化模式下复制文本块

1. 首先进入 visual 模式：v
2. 移动光标选择文本
3. 复制与粘贴的操作

## 插件
### Google：[vimium](https://chrome.google.com/webstore/detail/vimium/dbepggeogbaibhgnhhndojpepiihcmeb)

快捷键: 

- `shift` + `?` 帮助说明
- `f` 快捷链接打开页面
- `F` 快捷键打开新页面
- `gt` 下一个标签
- `gT` 上一个标签
- `H` 后退
- `L` 前进

### Sublime text

在菜单栏中： Preferences -> Setting - User ，即可打开配置文件进行编辑，将 ignored_packages 项的[]里面内容清空：

```json
{
    "ignored_packages":[]
}
```
### vscode：[vscodevim](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)
### idea: [ideavim](https://plugins.jetbrains.com/plugin/164-ideavim)

## 参考

[vim 简介和安装](https://www.zhaixue.cc/vim/vim-intro.html)

[Chrome插件Vimium使用教程](https://zhuanlan.zhihu.com/p/113316942)

[vim初步接触](https://www.learnfk.com/vim/vim-tutorial-intro.html)

[vim使用入门](https://www.zhaixue.cc/vim/vim-intro.html)