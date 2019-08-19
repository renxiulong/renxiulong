### git操作

1. 初始化
> git init
2. 添加文件
> git add filename
3. 提交文件
> git commit -m "注释内容"
4. 关联远程仓库(第一次使用,后面的wangjiax9/practice.git是在github上建立的仓库)
> git remote add origin git@github.com:wangjiax9/practice.git
5. 将本地库内容推送到远程库上(第一次需要-u参数，以后可以不要此参数)
> git push -u origin master

### git分支操作

1. 查看分支:`git branch`
2. 创建分支：`git branch <name>`
3. 切换分支：`git checkout <name>`
4. 创建+切换分支：`git checkout -b <name>`
5. 合并某分支到当前分支：`git merge <name>`
6. 删除分支：`git branch -d <name>`
7. 查看提交历史: `git log --graph --pretty=oneline --abbre-commit`