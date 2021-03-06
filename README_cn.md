# 我的 NeoVim 配置文件

[English version](./README.md)

此仓库包含我的个人 NeoVim 配置文件 (我是一个 [colemak](https://www.colemak.com) 用户)

如果你不能读懂这份配置, 请不要使用它, 否则你很有可能会遇到问题

![](./screenshots/1.png)

## 指南

<!-- TOC GFM -->

* [使用之前](#使用之前)
	- [检查 "健康"](#检查-健康)
	- [Python 程序调试 (通过 `vimspector`)](#python-程序调试-通过-vimspector)
	- [配置 `Python` 路径](#配置-python-路径)
	- [标签列表:](#标签列表)
	- [FZF (模糊文件查找器)](#fzf-模糊文件查找器)
	- [其它项...](#其它项)
* [键位](#键位)
	- [移动方式](#移动方式)
	- [其它按键](#其它按键)
* [其它相关项目](#其它相关项目)

<!-- /TOC -->

## 使用之前

- [ ] 安装 `pynvim` (pip)
- [ ] 安装 `nodejs`, 然后在终端输入 `npm install -g neovim`
- [ ] 安装 nerd-fonts (这是可选的, 不过它看起来十分棒)

### 检查 "健康"

你可以在 vim 中运行 `:checkhealth` 来检测你的 NeoVim 是否正常运转

### Python 程序调试 (通过 `vimspector`)
- [ ] 安装 `debugpy` (`pip`)

### 配置 `Python` 路径
- [ ] 确保你安装了 Python
- [ ] 查看 `_machine_specific.vim` 文件并根据情况做出更改

### 标签列表:
- [ ] 安装 `ctags` 以供应函数 / 类 / 变量的列表

### FZF (模糊文件查找器)
- [ ] 安装 `fzf`
- [ ] 安装 `ag` (`the_silver_searcher` 的依赖)

### 其它项...
- [ ] 安装 `figlet` 以打印 ASCII 艺术字
- [ ] 安装 `xclip` 以让 Vim 获得读取系统剪切板的能力 (仅需在 `Linux` 与 `xorg` 环境下安装)


## 键位

### 移动方式

上下左右的移动可以使用:

```
    ^
    u
< n   i >
    e
    V
```

移动五格光标可以使用:

```
    ^
    U
< N   I >
    E
    V
```
提示: `N` 与 `I` 键分别为移动至行首或行尾

### 其它按键

| 按键 | 功能                                              |
|------|---------------------------------------------------|
| k    | 切换至插入模式                                    |
| K    | 将光标移动至行首并切换至插入模式                  |
| l    | 撤销                                              |
| L    | Undotree (插件功能)                               |
| b    | 将光标移至上个词的首部                            |
| B    | 将光标移至上 5 个单词的首部                       |
| w    | 将光标移至下个单词的首部                          |
| W    | 将光标移至下 5 个单词的首部                       |
| h    | 将光标移至下个单词的尾部                          |
| tt   | 打开文件浏览器 (coc.nvim)                         |
| ts   | 翻译光标所在的单词 (coc.nvim)                     |
| S    | 保存一个在缓冲区中的文件                          |
| Q    | 退出编辑器或一个标签 (所有缓冲区都保存了的前提下) |


## 其它相关项目

- [dwm](https://github.com/KiteAB/dwm)
- [st](https://github.com/KiteAB/st)
- [scripts](https://github.com/KiteAB/scripts)
- [.config](https://github.com/KiteAB/.config)
