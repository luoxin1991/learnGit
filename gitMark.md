### 1 配置用户信息（ git config --global）

```shell
git config --global user.name 'your name'
git config --global user.email 'you email addr'
```

### 2 初始化（git init） 

```shell
git init
```

### 3 添加文件 （git add）

```shell
git add . #添加当前文件夹下的所有文件
git add readme.txt #添加指定文件
```

### 4 提交文件 (git commit )

```shell
git commit -m 'add a readme file'
```

### 5 查看仓库提交状态 (git status)

```shell
git status
```

### 6 查看文件改动信息 (git diff)

```shell
git  diff readme.txt
```

### 7 查看提交日志 ( git log)

```shell
git log
#以图形形式展开提交日志
git log --graph
```

### 8 版本回退 （git reset）

```shell
#一般先用 git log 查看提交日志，得到提交版本信息
git reset --hard 版本号（前四位就行）
```

### 9 查看被删除的提交的版本号（git reflog）

```shell
git reflog
```

### 10 撤销修改 （git checkout -- ）

```shell
git checkout -- gitMark.md
```

### 11 删除文件 （git rm）

### 12 添加远程仓库 （git remote add）

```shell
git remote add origin http://xxxx
```

### 13 从远程仓库克隆 (git clone)

```shell
git clone https://xxx
```

### 14 分支管理

```shell
查看分支：git branch
创建分支：git branch <branch name>
切换分支：git checkout <branch name>
创建+切换分支：git checkout -b <branch name>
合并某分支到当前分支：git merge <branch name>
删除分支：git branch -d <branch name>
删除一个没有合并的分支：git branch -D <branch name>
```

### 15 bug管理管理 (git stash)

```shell
#当有改动时，为了修复其他代码bug，可以使用git stash把改动隐藏起来
git stash
#使用git stash pop可以恢复现场
git stash pop
#使用git stash list 查看隐藏区信息
git stash list
```

### 16 忽略某些文件（.gitignore）

```shell
#在根目录下添加.gitignore文件可以忽略一些上传文件
```

### 17 查看谁在什么时间修改了文件 （git blame）

```shell
git blame <file name>
```



//修改罗鑫1990



//修改2 罗鑫1990

