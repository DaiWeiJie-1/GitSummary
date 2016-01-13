# Git使用总结

标签（空格分隔）： git

---

#查看分支
```
//查看本地分支
git branch 


//查看本地和远程分支
git branch -a
```

#创建分支与切换分支
```
//创建本地分支
git branch <local_branch_name>

//切换到本地分支(存在的前提下)
git checkout <local_branch_name>

//创建并切换本地分支
git checkout -b <local_branch_name>

//推送到同名远程分支(没有的话会自动创建同名远程分支)
git push origin <remote_branch_name>

//推送指定本地分支到指定远程分支
git push origin <local_branch_name> : <remote_branch_name>

```

#本地分支添加索引
```
//添加指定文件至该分支索引
git add <file_name>

//添加所有新增文件至该分支索引
git add --all
```

#本地提交   
```
//提交指定文件至本地分支
git commit -m "commit info" <file_name>

//提交所有修文件至本地分支
git commit -am "commit info"
```

#远程分支推送
```
//将本地分支推送到远程分支上
git push
```

#查看本地分支状态
```
//查看当前本地分支的状态(修改文件)
git status

//查看当前文件与上个版本的差异
git diff <file_name>
```

#查看版本变更信息
```
//查看所有版本信息(时间,提交者,版本号,版本信息)
git log

//查看所有版本的信息包括修改的文件和行数
git log --stat

//查看该版本的修改详情
git log -p commit_code

//查看该文件的修改历史
git log -p file_name
```





