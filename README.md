# hello-github

这是一个用于练习 Git 的仓库。

## 这个文件是干什么的

`README.md` 是仓库的门面，别人（以及几个月后的你自己）打开仓库第一眼看到的就是它。
写清楚「这是什么、怎么用」，是一个仓库最基本的好习惯。

## 日常开发循环

每次干活就是这四步：

```bash
git pull                          # 1. 先拉取云端最新改动
# ...改代码...
git add .                         # 2. 把改动放进暂存区
git commit -m "这次改了什么"        # 3. 存一个档
git push                          # 4. 推送到 GitHub
```

## 三个救命命令

```bash
git status            # 我现在处于什么状态
git log --oneline     # 历史提交列表
git diff              # 具体改了哪几行
```

迷路的时候先敲 `git status`，它会告诉你该做什么。

## 试试看

1. 把下面这行字改掉，保存文件
2. 敲 `git status`，看看 Git 发现了什么
3. 敲 `git diff`，看看它具体抓到了哪几行改动
4. 然后 `git add .` → `git commit -m "改了 README"`

当前进度：还没开始练习。
