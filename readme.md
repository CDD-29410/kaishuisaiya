#git是什么
集中式版本控制系统（cvcs）=>svn
分布式版本控制系统（dvcs）=>git

#git 的作用
在项目开发的进程中 对值得记录的时间节点进行“备份”方便后期恢复(后悔药)
方便团队协作开发

#git管理文件的三种状态
-已修改(modified):表示修改(新增、删除、改写)了文件，但还没保存到数据库中（红色）
-已暂存(staged):表示对一个已修改文件的当前版本做了标记，使之包含在下次提交的快照中
-已提交(committed):表示数据已经安全地保存在本地数据库中

#初次运行Git前的配置
配置用户名和邮箱
```bash
git config --global user.name "chendadian"
git config --global user.email "2941083950@qq.com"
```
```
git config --list
git config user.name
git config user.email
```

# 获取git仓库（repo）

-自行初始化git仓库（git init）

-克隆远程（服务器）仓库（git clone [repo_url]）

### 查看仓库状态

```
git status
```



```
git add .将所有文件放到暂存区(经常做的)
git commit -m "提交信息”将暂存区文件提交到仓库（某个功能完成的时候/在必要时候提交)
```

