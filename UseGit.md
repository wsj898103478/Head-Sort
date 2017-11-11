# Head-Sort
使用git：首先安装git，我使用的编译工具是IntelliJ IDEA，为了让终端Terminal可以使用git命令，我在File->Settings->Tools->Terminal->Shell path设置git安装
的下的bin目录下的bash.exe，例如D:\Git\bin\bash.exe;然后重启IntelliJ IDEA即可。
第一步： touch README.md
第二步： touch .gitignore
第三步:  git init  (git 初始化)
第四步:  git status (查看git状态)
第五步： git add .
第六步： git status
第七步： git commit -am 'first commit' (初次提交)
第八步:  git remote add origin SSH地址(例如:git remote add origin git@github.com:wdadj4358981038/Head-Sort.git)
第九步： git branch
第十步： git push -u origin master(会出现RSA警告，要去设置SSH keys)
第十一步： ssh-keygen -t rsa -C "your-github-email@.com"(一路默认下去)
第十二步：然后找到SSH keys的位置，windows是在users->admin->.ssh->id_rsa.pub,然后全部拷贝。
第十三步：打开github，点头像，找到Settings->SSH and GPG keys->new SSH keys,然后title任意，最后将拷贝的内容复制到keys保存即可
第十四步：git pull ()
第十五步：git push -u origin master (会出错，原因是版本太低)
第十六步: git push -u -f origin master(刷新github主页即可看到更新的内容)
第十七步：git branch
第十八步： git branch -r(可以看到远程的git分支)
第十九步： git checkout -b selectSort origin/master (selectSort:是分支的名字，可以根据自己需求命名；origin/master：表示selectSort是分支下的)
第二十步： git branch(即可查看分支)
最后一步：git push origin HEAD -u(将刚创建的分支发布到远程，刷新github即可看到)

选择排序

