git的使用命令

1.填写用户信息
git config  --global user.name "jiangchao"
git config  --global user.name "414345390@qq.com"

2.创建版本库
例如：需要存放的版本库所在的位置，
d/testgit
cd d          进入d盘

mkdir testgit ---- 创建文件目录

pwd ---查看文件目录路径

3.通过命令 git init 把这个目录变成git可以管理的仓库
git init 

4.把文件添加到版本库中
  <1> git add readme.txt --添加到暂存区里面去
  <2> git commit -m "readme.txt 提交"---是提交的注释 
  <3> git status ----通过命令git status来查看是否还有文件未提交	
  <4> git diff readme.txt ---查看文件改了什么内容。	