# Vagrant配置


1. 安装vagrant[下载](https://www.vagrantup.com/downloads.html),virtualbox,SecureCRTP[下载](http://download.pchome.net/internet/telnet/download-54.html)

2. 安装vagrant和virtualBox

3. 建立并进入开发环境目录

4. [下载](http://www.vagrantbox.es/)box选择低点的版本--Ubuntu lucid 32

5. 添加box `vagrant box add base` + 远端的box地址或者本地的box文件名,先下载到本地再添加速度会比较快

6. vagrant init

7. vagrant up # 启动环境,改写vagrantfile里面的config. vm.network :forwarded_port, guest: 3000, host: 3000以及vagrant的ID信息

8. 打开SecureCRTPortable # 新建Sessions 主机名为127.0.0.1,填写端口2222,账户密码等相关信息

9. sudo apt-get update

10. Install Git with Apt-Get command:sudo apt-get install git-core

11. 使用cmd 到D:develoment/Freetalks/ 运行 vagrant reload(`重启`)


# Vagrant 相关命令



1. `vagrant up` 开机

2. `vagrant halt` 关机

3. `vagrant reload` 重启


# Vagrant 使用


1. cd/挂载目录（在命令窗口中先去到Vagrant init 装载目录下才启动）

2. cd /vagrant 返回到计算机安装目录下


# git 相关的命令

1. `git config --global user.name "Your Name"` (安装完git后，设置用户名与邮箱)

2. `git config --global user.email "Your email"` (设置邮箱)

3. `ssh-keygen -t rsa -C "youremail@example.com"` (创建 SSH key)

5. `ssh-agent -s` (查看 ssh 是否启用)

6. `ssh -T git@github.com` (验证)
 
7. `git init` (初始化一个本地仓库)

8. `git add .` (将所有文件加入到跟踪列表)

9. `git commit -m "write something title"` (提交到本地仓库)

10. `git status` (查看git文件哪处发生改动)

11. `git remote add origin git@github.com:github账户名/github创建的库.git`(将本地仓库关联到github上远程仓库)

12. `git push -u origin master` (将本地仓库的所有内容推送到远程库上，下一次推送时直接 `git push`)

13. `git clone URL` (克隆远程仓库)

14. `git branch` (查看当前分支)

15. `git checkout -- filename` (文件恢复到最新版本，但丢失最近一次提交后你修改的内容)

16. `git checkout name` (切换分支，name 为分支名称)


# vim 相关命令


1. `vim filename` (打开编辑文件)

2. 按一下`i`键 (进行编辑文件)

3. 按一下`Esc`键 (退出i(插入)命令进行其它命令使用)

4. `:wq` (保存文件并退出)

5. `:q!` (强制退出,不保存)

6. `: w filename` (将文章以指定的文件名filename保存)






