# unity-
个人学习的记录
初始化本地仓库：git init
设置用户名： git config --global user.name  "用户名"
设置邮箱：git config --global user.eamil "邮箱"
查看基本配置：git config --list
生成ssh公匙：ssh-keygen -t rsa -C "邮箱"
设置上传文件允许大小：git config http.postBuffer 524288000


对比项目前后区别：git status
项目文件新建后执行添加进本地缓存：git add 文件名+后缀
本地项目修改内容合并：git commit
项目文件未新建只修改合并：git commit -a -m "修改原因或修改内容提示"
项目删除文件后执行：git rm 删除文件名+后缀
项目删除文件夹后执行：git rm 删除文件夹名称 -r

查看所有库名：git remote
查看库名及网址：git remote -v

查看所有分支：git branch
创建分支：git branch 新分支名称
创建分支的同时切换过去：git checkout -b 新分支名称
查看当前项目指向的分支：git log --oneline --decorate
切换分支（切换分支的同时项目目录会更换为目的分支的项目内容）：git checkout 分支名称
删除分支：git branch -d 分支名称

切换至指定版本（确定是当前分支）：git checkout 版本号


项目提交：例子：git push -u origin master   参数：origin（默认库名）master（默认分支名）

禁用 当前分支合并分支：git merge 合并分支名称
