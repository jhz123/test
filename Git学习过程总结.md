# Git学习过程总结  
## 下载及安装
在官网按步骤下载安装，网址为：<https://git-scm.com/downloads>
## 配置用户信息
    <$ git config --global user.name 'your_name'>
    <$ git config --global user.email 'your_email'>
## 建立Git仓库
1. `cd` 进入文件夹
2. `git init` 初始化  
3. `git add 'files'` 添加文件到暂存区
4. `git commit -m'备注内容'` 提交暂存区到本地仓库

补充：   
`git add . ` //添加所有文件到暂存区  
`git status` //查看项目的当前状态
## 建立远程仓库
1. 在**GitHub**上创建账户  
2. `git remote add origin 地址` 将本地仓库关联到github上  
3. `git pull origin master`  
4. `git push -u origin master` 上传代码到github仓库  
## 补充
- [git branch](https://blog.csdn.net/afei__/article/details/51567155)
- [git tag](https://www.jianshu.com/p/154d58451ef7)  
