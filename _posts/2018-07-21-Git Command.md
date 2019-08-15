# Git使用基本命令 #
1. git add "filename" 
2. git commit -m "注释"
3. git push
4. git status 查看修改文件的状态  
5. git push -f 强制上传

---
### 基本流程
首先使用git add命令添加文件，然后git commit提交到本地仓库，然后使用git push命令提交到github远程服务器上。

---
下面详细讲解git add  
  
* 添加一个文件 git add file1.txt
* 添加多个文件 git add file1.txt file2.txt file3.txt

---

从头开始的话，这里什么都没有，咋办？   

	1.创建一个空目录
	2. git init初始化工程
	3. git add
	4. git commit -m "写自己的注释"
	5. git push // 提交到远程服务器