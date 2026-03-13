> 更新时间：2026年3月14日

> 主要内容：同步Github笔记的Git使用方法

---

# 推送

```bash
gitadd.# 把所有修改的文件加入暂存
git commit -m"新增Python基础语法笔记"# 提交修改，写清楚备注
git push   # 推送到GitHub仓库
```

# 报错

* `Everything up-to-date`：本地没有新的提交（没执行 `git add`/`git commit`）；
* `Permission denied (publickey)`：SSH 密钥配置错误；
* `Connection was reset`：网络拦截（仍需切换手机热点）；
* `fatal: The current branch main has no upstream branch`：分支未关联。

