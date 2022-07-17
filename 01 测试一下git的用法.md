## **测试一下git的用法**

- ### **克隆仓库到本地**：

1. 第一步：在电脑上安装git软件。
2. 第二步：在电脑上存放仓库的文件夹下，右键鼠标-》git bash here。
3. 第三步：使用采用 git clon :远程仓库的地址。
4. 第四步：git pull //更新本地仓库

- ### 将本地仓库上传到github

1. 第一步：git add . //这里表示将上传内容添加到缓存仓库
2. 第二步：git commit -t '上传操作的评论'
3. 第三步：git push //正式上传的远程仓库

**注意**：

如果没有授权，按如下操作

- 执行 ssh-keygen -t rsa -C "你的git注册邮箱"，在 .ssh 目录下会生成以下3个文件：
                  id_rsa，  id_rsa.pub，  known_hosts
- 这三个文件的地址：/c/Users/Administrator/.ssh/id_rsa
- 在浏览器登录github，在Settings界面点击左边的 SSH and GPG keys，然后复制  id_rsa.pub 文件的内容到SSH keys，点击Add SSH key即可。
- 执行 ssh -T git@github.com，就能看到成功了。
  
  ==在github上添加内容，然后跟新本地仓库==
