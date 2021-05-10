---
layout: post
title: "Mastering Vim"
date: 2021-05-10
---

<p align="center">
<img src="https://miro.medium.com/max/1022/0*6ve47nqg93ZzZxws.png" width="100" height="100" border="10"/>
</p>
So, I thought to my self, why not start a blog. A blog about the things, I love doing. The first thing I needed was a good text editor. And then here it is, my first blog about the text editor. Dennis Simpson and his [courses](https://zonzorp.github.io/) about Information System Security introduced me to the Linux world. The guy was a wizard with Vim. I wished to be like him. Here I am now, with [The Ultimate Markdown Cheat Sheet](https://towardsdatascience.com/the-ultimate-markdown-cheat-sheet-3d3976b31a0) and the book **Mastering VIM** by Ruslan Osipov hoping one day I will be like Dennis.

***
## Vim
A modal interface, where each trigger performs a different action based upon context. 

### Setting up on Linux
```
git clone https://github.com/vim/vim.git
cd vim/src
make
sudo make install
```
We can update Vim using a package manger as well.
```
sudo apt-get update
sudo apt-get install vim-gtk
```
We can start the editor by typing `vim` or `vi`. On older systems the two are different binaries.
### Verifying installation and trouble shooting
```
vim --version
```
In output, a set of features having a + and a - infront of them will be shown. For example, Vim if complied with Python 2 support will dispaly (+python) instead of Python3 support (-python3)

I am not gonna talk about the .vimrc files. It is a different world. It is the configuration file for Vim where we can configure things like syntax highlighting, consistent indentation etc.
>`I've been using Vim for about 2 years now, mostly because I can't figure out how to exit it.`






