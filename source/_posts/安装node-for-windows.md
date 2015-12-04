title: 安装node_for_windows
description: 安装node_for_windows
toc: true
date: 2015-12-04 15:05:06
tags: [node, windows]
---

# 安装nvm for windows
 
https://github.com/coreybutler/nvm-windows
https://github.com/coreybutler/nvm-windows/releases
 
# 安装nodejs
 
```bash
nvm install latest 32
nvm use 5.1.1 32
```
 
# 安装cnpm
 
https://github.com/cnpm/cnpm
 
```bash
npm install cnpm -g
```
 
# 安装hexo
 
https://hexo.io
 
```bash
cnpm install hexo-cli -g
cd
mkdir hexo
hexo init hexo
 
```
 
# 安装maupassant
 
https://www.haomwei.com/technology/maupassant-hexo.html
 
```bash
cd ~/hexo
git clone https://github.com/tufu9441/maupassant-hexo.git themes/maupassant
cnpm install hexo-renderer-sass --save
cnpm install hexo-renderer-jade --save
```
 
