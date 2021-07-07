### 1、安装Git

1、安装git在https://git-scm.com/download/win

2、默认下一步

3、检验是否安装好（只需要右击空白区看看有没有git bash here即可）

### 2、git的使用基本流程

1、在.git的文件中同等目录下新建文件（文件名。后缀名）

2、将文件从工作区提交到暂存区

​      从工作区提交到暂存区

​     先查看文件状态：输入命令行：git status

​      再提交到暂存区：输入命令行：git add 文件名.后缀名

3、将文件从暂存区提交到仓库

​      先看文件状态： 输入命令 ： git status

​      在提交文件：     输入命令：git commit -m"提交描述，在github中提交项目都会有描述

​      在输入命令 ： git status 查看文件状态



 具体操作                                  

1. 在终端输入文件： touch 文件名.文件类型(c,c++)   //新建一个编程代码文件，只是一个文件，没有内容



2. 从工作区到暂存区
   输入命令：git status
   输入命令：git add 文件名.文件类型(c,c++)



3. 从暂存区到仓库
   输入命令：git status
   输入命令：git commit -m 'add a.php(文件的相关描述)'
   输入命令：git status(查看是否提交成功 )



### 3、Git管理远程仓库

1. 在git文件夹中打开git bash here

2. git init

3. 输入命令：git clone 仓库地址

4. 同步成功后，对文件进行一系列操作

5. 将文件从工作区提交到暂存区

6. 将文件从暂存区提交到仓库

7. 将本地仓库同步到git远程仓库中，输入命令git push

   