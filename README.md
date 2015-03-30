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
 
3. `git init` (初始化一个本地仓库)

4. `git add .` (将所有文件加入到跟踪列表)

5. `git commit -m "write something title"` (提交到本地仓库)

6. `git status` (查看git文件哪处发生改动)

7. `git remote add origin git@github.com:github账户名/github创建的库.git`(将本地仓库关联到github上远程仓库)

8. `git push -u origin master` (将本地仓库的所有内容推送到远程库上，下一次推送时直接 `git push`)

9. `git clone URL` (克隆远程仓库)






