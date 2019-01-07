# git-operator-test
study git operator


1、 mkdir git-operator-test
2、cd git-operator-test
3、git init
4、git config --global user.name 'mayunzhen'
5、git config --global user.email '632940781@qq.com'
6、touch 1.cpp
7、git add 1.cpp
8、git commit -m 'add 1.cpp'
9、添加id_rsa.pub内容到github主页的settings中；
10、git push -u origin master -f （-f是强制的意思）
11、git checkout -b feature1
12、git push origin feature1
13、make a new follder and execute : 
git clone https://github.com/mayunzhen/git-operator-test.git -o booyah
Then ,execute :git status ,look:
On branch master
Your branch is up to date with 'booyah/master'.

Expand:
# 查看关联的远程仓库的名称
git remote
# 查看关联的远程仓库的详细信息
git remote -v
# git_url 为你的远程仓库的 url，可采用 http 协议或 ssh（git） 协议
git remote add origin <url>
git remote remove <name>


