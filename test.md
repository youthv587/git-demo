git操作练习
git init			//初始化
git add README.md	//使用add命令添加文件
git commit -m "first commit"   //提交到仓库
git commit -a -m "Changed some files"  //提交多个已修改文件
git remote add origin git@github.com:youthv587/git-demo.git    //添加远程地址
git push -u origin master    //提交到远端仓库

<<<<<<< HEAD

git reset 命令分为两种： git reset –-soft 与 git reset –-hard ，区别是：
前者表示只是改变了HEAD的指向，本地代码不会变化，我们使用git status依然可以看到，
同时也可以git commit提交。后者直接回改变本地源码，不仅仅指向变化了，代码也回到了那个版本时的代码。

 执行 git push origin 分支名 –-force ，强制提交当前版本号
 
 
=======
add 
>>>>>>> e515c642216144166242f45c23092e02aca71307
