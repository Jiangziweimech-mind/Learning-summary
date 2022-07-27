## github学习笔记

**Repository  仓库**

仓库用来存放项目代码，每个项目对于一个仓库，多个开源项目测有多个仓库

**star 收藏**

收藏项目，方便下次查看

**fork   复制克隆项目**

<img src="git学习笔记.assets/image-20220503185135408.png" alt="image-20220503185135408" style="zoom:50%;" />

tips：该fork的项目是独立存在的

**Pull Request 	发起请求**

<img src="git学习笔记.assets/image-20220503195311020.png" alt="image-20220503195311020" style="zoom:50%;" />

**Watch	关注**

项目更新就会第一时间收到通知提醒

**Issue	事务卡片**

发现代码bug，就可以给提问题



### 创建仓库

​						 <img src="git学习笔记.assets/image-20220503201632095.png" alt="image-20220503201632095" style="zoom: 67%;" />

### 仓库主页

<img src="git学习笔记.assets/image-20220503205751914.png" alt="image-20220503205751914" style="zoom: 67%;" />









![image-20220503210725384](git学习笔记.assets/image-20220503210725384.png)

### Github Issues

<img src="git学习笔记.assets/image-20220503213512432.png" alt="image-20220503213512432" style="zoom:50%;" />



<img src="git学习笔记.assets/image-20220503213655969.png" alt="image-20220503213655969" style="zoom: 67%;" />

<img src="git学习笔记.assets/image-20220503214007299.png" alt="image-20220503214007299" style="zoom:67%;" />







### Git基本工作流程



<img src="git学习笔记.assets/image-20220504095031125.png" alt="image-20220504095031125" style="zoom: 50%;" />





<img src="git学习笔记.assets/image-20220504100502124.png" alt="image-20220504100502124" style="zoom:50%;" />



### 对本地仓库操作

#### Git初始化

**设置用户名** 		git config --global user.name 'username'

**设置用户名邮箱	**	git config --global user.email 'email'



初始化仓库 git init

查看提交状态   git status

提交到暂存区 git add

将文件从暂存区提交到仓库 git commit -m '提交描述'

<img src="git学习笔记.assets/image-20220504104343904.png" alt="image-20220504104343904" style="zoom: 67%;" />



### 对远程仓库操作

<img src="git学习笔记.assets/image-20220504110035175.png" alt="image-20220504110035175" style="zoom:67%;" />

**克隆**		git clone  仓库地址	

**推送** 		git push 

**git常用指令：**https://blog.csdn.net/c_playboy/article/details/71425531







### 5个隐藏的Github技巧

1、github搜索技巧：https://blog.csdn.net/wangxueying5172/article/details/120260848

2、按t 对仓库内所有文件进行搜索   按L 快速跳转到某一行  按b查看该文件的改动记录

![image-20220509112059906](git学习笔记.assets/image-20220509112059906.png)

3、在仓库界面按下  ‘。’ 在网页版的vscode上打开了

4、![image-20220509112330666](git学习笔记.assets/image-20220509112330666.png)

5、explore中可以设置定期给邮箱推送优质项目







git log

git reset --hard e9ed30024eb733c598df7814e424491445997088

git push -f origin Branch_jzw

git pull origin master

git push -f origin Branch_jzw
