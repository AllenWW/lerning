# lerning

notes

## github 学习笔记
1安装使用开始
https://blog.csdn.net/qq_41782425/article/details/85183250
最新GitHub新手使用教程(Windows Git从安装到使用)——详细图解

https://blog.csdn.net/iwuyuetian/article/details/82894318
Git使用教程：最详细、最傻瓜、最浅显，小白都能看懂
$ cd d:/testgit


https://blog.csdn.net/rj597306518/article/details/71307757
【Github教程】史上最全github使用方法：github入门到精通


ww@DESKTOP-J62SIEV MINGW64 /d/testgit
$ pwd
/d/testgit

ww@DESKTOP-J62SIEV MINGW64 /d/testgit
$ git init
Initialized empty Git repository in D:/testgit/.git/

ww@DESKTOP-J62SIEV MINGW64 /d/testgit (master)

注意：
配置SSH Key 命令
在Git终端在输入ssh-keygen -t rsa -C "youremail@example.com" ( GitHub上注册时的邮箱
-C 要大写
需要先创建分支之后才能备份到本地??


要在根目录上去进行CLONE.

学习笔记更新

提交步骤
ww@DESKTOP-J62SIEV MINGW64 /d/testgit/lerning (master)
$ git add .

ww@DESKTOP-J62SIEV MINGW64 /d/testgit/lerning (master)
$ git commit -m 学习更新
[master a6583bc] 学习更新
 1 file changed, 4 insertions(+)

ww@DESKTOP-J62SIEV MINGW64 /d/testgit/lerning (master)
$ git push origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 355 bytes | 355.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/AllenWW/lerning.git
   672a47c..a6583bc  master -> master

