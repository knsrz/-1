# git 使用总结

配置

git config --global  user.name "用户名"
git config --global user.email "邮箱"

生成公钥

ssh-keygen -t rsa -C "邮箱"



1.初始化 git

git init

2.添加单个文件 并提交

git add 文件名

git commit -m '你的描述'

3.添加添加当前目录所有文件的更改

git add .

4.连接到你的某个github仓库

git remote add origin  (有两种方式 http:\\开头的地址 和 ssh方式)

5.将github仓库中的内容先同步到本地

git pull  --rebase origin master

6.将本地提交到github

git push origin master





# 其它命令

状态检查

git status

添加当前目录所有文件

git add -A

选择要添加的更改（输入Y和N来判断）

git add -p

详细内容    https://zhuanlan.zhihu.com/p/94008510?utm_source=wechat_session&utm_medium=social&utm_oi=614887696682848256

解决GitHub每次push时都提示输入用户名和密码的问题 https://blog.csdn.net/Mr_JavaScript/article/details/83043174

