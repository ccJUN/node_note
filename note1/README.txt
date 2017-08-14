由于本人工作和开发都在mac下，建议在Linux或者Mac下开发。
安装方法:

1.通过node官网下载
https://nodejs.org/en/download/
download下载

window下经常会遇到配置环境问题：
附上配置环境的解决方案
window下的问题:
http://www.jianshu.com/p/03a76b2e7e00

2.Mac下
通过brew下载（推荐方案），一般不会有环境问题

brew update
brew install node

如果mac下没有命令brew命令，安装brew的命令：
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

参考网址：
https://brew.sh/

node版本管理和ruby版本管理是十分相似的，这里一并说下：

node版本管理工具：nvm
ruby的版本管理:rvm

安装方式都是通过brew安装的：

安装命令：
brew install nvm
//环境配置
export NVM_DIR=~/.nvm
source $(brew --prefix nvm)/nvm.sh
source .bash_profile

ruby也一样：
$ curl -L get.rvm.io | bash -s stable
$ source ~/.rvm/scripts/rvm
参考了文章:
https://segmentfault.com/a/1190000003784636

本人在安装过程十分顺利，如果会造成问题的，一般都是因为安装了oh-my-zsh，有些环境配置问题，作者叶装了oh-my-zsh的没有遇到这种情况
https://segmentfault.com/a/1190000004404505


