### 将本地项目上传到github
- 本地仓库
```
git init #在本地创建一个git仓库
git add . #将项目添加到暂存区
git commit -m "注释内容" #将项目提交到Git仓库
```
- 远程仓库
```
添加ssh key
新建repositories
```

- 本地仓库
```
git remote add origin git@github.com:UserName/projectName.git #将本地仓库与远程仓库关联；
git push -u origin master #将本地仓库推送到远程仓库
```

### 设置用户信息
在git终端输入命令设置用户信息
```
git config --global user.name "name"
git config --global user.email "email"
```
查看当前设置
```
git config --list
```



