#git学习命令 2020.6

##添加文件
git add [filename]

##提交文件
git commit -m '[注释]'

##查看工作状态
git status

##查看修改信息
git diff [filename]

##查看提交日志
git log [--pretty=oneline]

##版本回退
git reset --hard [commit id]

##git记录的每次命令
git reflog

##删除文件
git rm [filename]
再通过commit提交一次

##丢弃工作区的修改
git checkout -- file

##撤销暂存区修改
git reset HEAD <file>

##创建SSH Key
ssh-keygen -t rsa -C "youremail@example.com"

##关联一个远程库
git remote add origin git@server-name:path/repo-name.git

##第一次推送master分支的所有内容
git push -u origin master
第二次之后就不用再加 -u 了

##克隆一个仓库
git clone git@server-name:path/repo-name.git