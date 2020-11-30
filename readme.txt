学习git的使用
新建git仓库

git init  初始化仓库
git add 文件名字.文件后缀  添加文件到仓库 （可多次添加或者添加多个 添加时将要添加的文件放在 初始化仓库的文件夹下）
git commit -m "更新或者上传信息，随自己填写" 

要关联一个远程库，使用命令git remote add origin git@server-name:path/repo-name.git；（path是你的账号名：codeeding  repo-name是这个仓库名字：git_repository）

关联后，使用命令git push -u origin master第一次推送master分支的所有内容；

此后，每次本地提交后，只要有必要，就可以使用命令git push origin master推送最新修改；
