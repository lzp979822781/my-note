一次性提交所有分支
现在手上有两个分支，master和rotation，想一次性推送所有分支，可以用--all参数来实现：

git push --all origin
如果远程仓库有更改，但你需要直接推送，那就可以使用强覆盖方式（-f参数）用你本地的代码替代git仓库内的内容：

git push -f
结合起来：

git push --all origin -f
