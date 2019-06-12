This is my first time to learn git.
git init
git add <file>
git commit -m <message>

This is my second time to write.
git status  //查看是否有改变
git diff <file>     //查看改变了什么
git add <file>
git status
git commit -m <message>
git status
git log //查看更新历史
cat <file>  //查看file内容

test
git reset --hard HEAD^  //退回上一版本
git reset --hard <version> //返回指定版本
git reflog  //记录每次命令

basis
//此电脑的工作区为Git-learn,工作区中隐藏文件.git为Git的版本库
//版本库中有一个暂存区stage和一个分支master,一个指针HEAD指向master
//git add 把文件添加到暂存区stage，git commit 将其添加到分支
git checkout --<file>   //丢弃最近一次工作区修改
git reset HEAD <file>   //丢弃最近一次暂存区修改
