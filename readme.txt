git上传过程：

1、$ git add XX: 
## xx指示是添加某个文件

2、$git commit -m "xx"：
##指的是为文件做一个简短的说明；

3、$git push
##输入命令把文档输入GitHub上；

eg：修改和增加代码并推送

## 添加所有修改的文件，也可以git add xx.txt 指定某个文件
$ git add .
## 提交修改
$ git commit -m "update"
## 推送到远程仓库
$ git push 


使用说明：
git push  ##上传git账号
git clone https://github.com/xxxx/xxxx.git  ##克隆其它使用者的账号资料；https://github.com/xxxx/xxxx.git：资料地址；
$ git status：查看状态；
$ git commit -m "update" ## 提交修改
git add xx  ##新建某个文件 ；按回车；
git commit -m"the first version"回车，接着git statu：查看文件的修改；
git reflog：查看修改历史；
cd xx:新建一个文档；xx指的是文件夹名称；

$ git branch test：## 新建一个test分支
$git mkdir demo：##新建一个工作目录；