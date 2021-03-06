# git 使用说明
初始化
```
git init
```
创建文件
```
touch i.js
```
提交暂存区
```
git add .
```
提交
```
git commit -m 第一次提交
```
编辑历史区
```
vi 1.js
```
再提交
```
git add commit -a -m 第二次提交
```
 创建并切换分支
```
git checkout -b dev
```
在编辑
```
vi 1.js
```
提交到哪个分支就切换到哪个分支提交
```
git add commit -a -m 第三次提交
```
切换到master分支，然后合并分支
```js
git checkout master
git merge dev
```

1. 删除远程分支
> git push origin --delete 分支名

2. 删除本地分支
> git branch -d 分支名

3. 重命名本地分支
> git branch -m 原分支名 新分支名

4. 推送本地分支
> git push origin 分支名

5. 查看远程分支
> git branch -a

6. 查看本地分支
> git branch

7. 新建本地分支
> git branch 分支名

8. 切换本地分支
> git checkout 分支名

9. 重命名远程分支
> 在git中重命名远程分支，其实就是先删除远程分支，然后重命名本地分支，再重新提交一个远程分支。

10. 根据远程分支创建本地分支
> git checkout -b 分支名 origin/分支名

## 最后

### 喜欢的小伙伴们请点一下右上脚star按钮:star:，就可以收藏这篇文章啦！，如果你有更好的前端知识需要和我一起分享，请点fork按钮，提交你的资料吧！如果想在第一时间获取我的更新，并且每次更新会有提醒，请点watch按钮。
