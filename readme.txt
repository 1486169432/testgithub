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

5.版本回退
<1> git log(git log –pretty=oneline) ---显示从最近到最远的显示日志	
<2> git reset  --hard HEAD^ ---回退到上一版本
<3> git reset  --hard HEAD^^ ---回退到上上个版本
<4> git reset  --hard HEAD~100  ---回退到第100个版本
<5> git reset  --hard ---版本号
<6> git reflog  ----查看修改内容的版本号
<7> git reset  --hard 6fcfc89 ---回退到指定的版本号


6.Git撤销修改和删除文件操作。
<1> git checkout  -- readme.txt(文件名)  ---，把readme.txt文件在工作区做的修改全部撤销