
### 常用命令

拉取一个仓库
```shell
git clone git@gitee.com:flash127/docker.git
```

当前的状态
```shell
git status
```

下载远程代码并合并
```shell
git add . && git commit -m '本次修改内容'
```

推送到远程仓库`test`分支
```shell
git push origin test
```

拉取远程分支
```shell
git pull
```

查看近5次提交
```shell
git log -5
```

回滚到某次提交
```shell
git reset 4205453926xxxx
```

创建分支
```shell
git branch 
```

切换分支
```shell
git checkout test
```

将test分支合并到当前分支
```shell
git merge test
```

查看标签
```shell
git tag
```

添加标签
```shell
git tag v1.0.0
```

推送标签到远程仓库
```shell
git push --tag
```



