---
title: hexo+Next主题
date: 2019-03-24 16:35:33
tags: hexo
---
## 在github pages根目录建立hexo博客
_config.yml配置：
<code>
deploy:
  type: git
  repo: https://github.com/bjrobin/bjrobin.github.io.git
  branch: master
</code>
访问：https://bjrobin.github.io/

## 在github pages子目录建立hexo博客
建立blog仓库
本地：git clone git@github.com:bjrobin/blog.git
进入目录：cd blog
在本地新建一个分支：git branch gh-pages
切换到你的新分支：git checkout gh-pages
_config.yml配置：
<code>
deploy:
  type: git
  repo: https://github.com/bjrobin/blog.git
  branch: gh-pages
</code>
将新分支发布在github上：git push origin gh-pages
访问：https://bjrobin.github.io/blog/

## Hexo 博客绑定个人域名子目录
_config.yml配置：
<code>
deploy:
  type: git
  repo: blog@182.92.232.130:/usr/local/lianghuaquan/git/blog.git
  branch: master
</code>
访问：http://www.lianghuaquan.com/blog/

## Hexo 博客绑定个人二级域名
访问：http://blog.lianghuaquan.com