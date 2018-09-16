##### 创建分支

```
git checkout -b 分支名

＃相当于执行下面两条命令
git branch 分支名
git checkout 分支名
```

##### 将本地分支同步到远端

```
git push origin　远程分支
```

##### 查看分支

```
git branch
```

##### merge远程分支

```
git merge origin/分支名
```

##### 回滚代码到指定分支

```
＃查看提交记录
git log
＃回滚
git reset --hard commitId
```

