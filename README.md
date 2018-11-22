# jstest
第一次提交
1.在命令行中，输入“git init”，使Test文件夹加入git管理；
2.输入“git add .”（不要漏了“.”），将Test文件夹全部内容添加到git。
3.输入“git commit -m "first commit"”（“git commit -m "提交信息"”）
4.输入“git remote add origin https://github.com/maplelafe/jstest.git”（git remote add origin 你自己的https地址），连接你的guthub仓库。
5.输入“git push -u origin master”，上传项目到Github。这里会要求输入Github的账号密码，按要求输入就可以

第一次提交错误
1、在使用git 对源代码进行push到gitHub时可能会出错
2、出现错误的主要原因是github中的README.md文件不在本地代码目录中
3、可以通过如下命令进行代码合并【注：pull=fetch+merge]
git pull --rebase origin master
4、执行上面代码后可以看到本地代码库中多了README.md文件
5、此时再执行语句 git push 即可完成代码上传到github


提交代码：
1、在本地修改相应文件（或者文件新旧替换）
2、git add **/**/文件名    （文件修改路径）（注意路径要写对）
3、git status         ----查看当前本地文件信息
4、 git commit -m "更改信息备注"
5、git push               --------提交代码到当前分支

