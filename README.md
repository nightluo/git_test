<!--
 * @Author: nightluo 1872194982@qq.com
 * @Date: 2023-03-31 14:40:35
 * @LastEditors: nightluo 1872194982@qq.com
 * @LastEditTime: 2023-03-31 14:42:02
 * @FilePath: /project/git_test/README.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
# git_test

create a new repository on the command line
echo "# git test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/nightluo/git_test.git
git push -u origin main

create a new repository on the command line
git remote add origin https://github.com/nightluo/git_test.git
git branch -M main
git push -u origin main

远程分支与当前分支合并
git pull origin master
将远程主机 origin 的 master 分支拉取过来，与本地的 brantest 分支合并
git pull origin master:brantest

本将本地的 master 分支推送到 origin 主机的 master 分支
git push origin master
git push origin master:master


