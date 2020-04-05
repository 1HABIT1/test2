## Git安装

## 初始化Git仓储/(仓库)
 - 这个仓库会存放，git对我们项目代码进行备份的文件
 - 在项目右键打开 git bash
 - 命令：'git init'

## 自报家门
 - 命令：
    + 配置用户名：'git config --global user.name "liuhua"'
    + 配置邮箱：'git config -- global user.email "xxx@xxx.com'

## 把代码存储到.git仓库中
 - 1. 把代码放到仓储的门口
    + 'git add ./readme.md'   将指定文件放到大门口
    + 'git add ./' 把所有修改的文件都添加到大门口
 - 2. 把仓储门口的代码放到里面的房间里去
    + 'git commit -m "这是对这次添加东西的说明"'

## 可以一次性把我们修改的代码全都提交上去（版本库）


## 查看当前的状态
 - 用来查看当前代码有没有被添加到仓库里
 - 命令：'git status'
 
