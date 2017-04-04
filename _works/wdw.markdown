---
layout: post
title: "Web Dev Weekend"
thumbnail: wdw.png
date: 2016-03-16
tag: event
---

## Introduction

If you are viewing this site, chances are it is Saturday, April 9th, 2016 and you are attending Dzgn.IO's Web Development Workshop. If not, welcome strange visitors! <span class="emoji emoji-alien"></span> This also means you've taken the leap and have decided that you want to create your own website - YESS!! <span class="emoji emoji-thumbs_up"></span> We're here to help!

This workshop will cover the basics of programming in HTML and CSS. We will then turn up the heat and discuss templating webpages with <a href="https://jekyllrb.com/" target="_blank">Jekyll</a>.

You can view the presentation <a href="https://docs.google.com/presentation/d/1atVlVMFR8oGAXJKRoR78Op2sxHMyvD-DqhUKsNTeGpM/edit?usp=sharing" target="_blank">HERE</a> for reference.

## Skills We'll Learn

* Setting up your development environment
* HTML &amp; CSS
* Using Jekyll
* Markdown

## Your Dev Environment

...is sacred - preach. <span class="emoji emoji-pray"></span>

Jokes aside, your development environment will take some preparation. For our workshop, we will be setting everyone up with Brackets, an open source text editor, and Jekyll, the Ruby-based gem.


### Installing Brackets

Visit <a href="http://brackets.io/" target="_blank">brackets.io</a> to view the brackets project site. Please download the most recent version of Brackets with or without Extract.


### Installing Git (Windows Only)

Download and install <a href="https://github.com/git-for-windows/git/releases/download/v2.8.1.windows.1/Git-2.8.1-64-bit.exe" target="_blank">this</a> version of Git for Windows. Do not change any options on the installer - the defaults are the ideal settings.


### Installing Jekyll

Jekyll runs on the Ruby programming language. Both Windows and Mac users will need to install Ruby, but the process is quite different depending on your OS.


{% highlight terminal%}
  #  Mac Users     
  #  Open Terminal on Mac and install Homebrew by running

  ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

  # Update to the newest Ruby

  brew install rbenv ruby-build
  echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi' >> ~/.bash_profile
  source ~/.bash_profile
  rbenv install 2.2.3
  rbenv global 2.2.3
  ruby -v

  # Install Jekyll

  gem install jekyll


  #  Windows Users

  #  Download <a href="http://dl.bintray.com/oneclick/rubyinstaller/rubyinstaller-2.2.4-x64.exe">this</a> version of Ruby
  #  Install the package, ensuring to check the "Add Ruby Executables to your PATH" box
  #  Open GitBash (installed with Git for Windows) and run

  gem install jekyll
{% endhighlight %}



## Resources
* <a href="https://docs.google.com/presentation/d/1atVlVMFR8oGAXJKRoR78Op2sxHMyvD-DqhUKsNTeGpM/edit?usp=sharing" target="_blank">The Presentation</a>
* <a href="https://jekyllrb.com/" target="_blank">Jekyll Documentation</a>
* <a href="https://jekyllrb.com/" target="_blank">Markdown Cheatsheet</a>
* <a href="http://www.w3schools.com/html/default.asp" target="_blank">HTML Tutorials</a>
* <a href="http://www.w3schools.com/css/default.asp" target="_blank">CSS Tutorials</a>
* <a href="https://github.com/eddymankim/testSite" target="_blank">Eddy's Test Site</a>
