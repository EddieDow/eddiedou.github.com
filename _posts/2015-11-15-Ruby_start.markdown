---
layout: post
title:  "Ruby 初学"
date:   2015-11-15 18:51:25
categories: Ruby
---
 
 
 * ##Homebrew

在Mac上准备Ruby环境之前，推荐安装Homebrew(<a href="http://www.amazon.cn/%E4%BB%8A%E9%98%85%E2%80%A2%E7%BB%8F%E6%B5%8E-%E4%BD%A0%E6%89%80%E4%B8%8D%E7%9F%A5%E9%81%93%E7%9A%84%E5%86%B0%E5%86%B7%E7%BB%8F%E6%B5%8E%E7%9C%9F%E7%9B%B8-%E8%A2%81%E6%B5%A9/dp/B007P7RK04" target="_blank">官网</a>),只需一行
  <pre><code>ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
</code></pre>

* ##Xcode

预先安装Xcode，因为后面会用到相关的command line tools

 
 * ##RVM
 
登录<a href="http://www.rvm.io/" target="_blank">官网</a>，可以看到安装RVM需要两步，第一步：
<pre><code>gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3
</code></pre>

安装过程中如果遇到错误 “gpg: command not found” error during RVM installation?

请在Terminal 内运行下面命令
<pre><code>brew install gnupg gnupg2</code></pre>

关于： GnuPG (with binary name gpg) is an application used for public key encryption, but also verification of signatures (cryptographic signatures, that also can validate the publisher if used correctly).

第二步骤
<pre><code>\curl -sSL https://get.rvm.io | bash -s stable</code></pre>



安装完毕后 在终端内运行以下命令，可以看到本地的Ruby 版本。
<pre><code>rvm -v</code></pre> 

本地安装版本列表命令 。
<pre><code>rvm list</code></pre> 
远端可用Ruby版本列表命令 
<pre><code>rvm list —remote
</code></pre> 
 

 * ##开发工具
 
 喜欢使用IDE的推荐使用RubyMine，当然你也可以用Vi,Sublime等文本工具。
 
 
  * ##更多
  

 Gem = Ruby标准库

ri 命令行工具查看文档

<pre><code>ri —server 
</code></pre> 

在浏览器内键入就看查看本地文档
<pre><code>http://localhost:8214/
</code></pre> 
   



  
  
