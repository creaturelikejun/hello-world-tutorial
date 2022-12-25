# hello-world-tutorial
In this respository,I'll start a project to show how to build a Hello world frame
repo:仓库，有多个项目，就建立多个repo
issue：问题；
star:点赞；
Fork:拉分支，复制相同的项目，独立于原项目，便于自己开发
pull request:提交请求
Merge:合并
Watch：观察
gist:单纯的分享代码片段？
1.用git status随时查看仓库的状态，
2.首先用git init初始化仓库；3.
在仓库中新建文件提交至远程仓库时，需要git add xxx提交到临时缓冲区(如git add hit.txt),
4.再用git commit提交到仓库，git commit -m "text commit";
5.git log可以打印git仓库提交日志
6.git branch查看仓库的分支情况（可用git branch a 创建新分支）
7.git checkout a，切换至a分支；git checkout -b 创建分支b，并切换到b
8.git merge融合a分支至master
9.gitbranch -d a删除a分支
10.git tag为分支添加标签（git tag v1.0）
终于解决了怎么将本地文件仓库同步至github远程仓库，在.git文件夹中，找到config文件，添加[user]邮箱和名字。或者在git bash here中输入邮箱和查看本地配置（https://blog.csdn.net/weixin_40599276/article/details/92702070），git add,git commit,再git push origin一下就可以(选好master或者main)
验证ssh是否完成git与github的绑定
ssh -T git@github.com    复制ssh，而不是http
即把hello world-tutorial同步到本地仓库
