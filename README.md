# Vagrant配置


1. 安装vagrant[下载](https://www.vagrantup.com/downloads.html),virtualbox,SecureCRTP[下载](http://download.pchome.net/internet/telnet/download-54.html);
2. 安装vagrant和virtualBox;
3. 建立并进入开发环境目录;
4. [下载](http://www.vagrantbox.es/)box选择低点的版本--Ubuntu lucid 32;
5. 添加box `vagrant box add base` + 远端的box地址或者本地的box文件名,先下载到本地再添加速度会比较快;
6. vagrant init;
7. vagrant up # 启动环境,改写vagrantfile里面的config. vm.network :forwarded_port, guest: 3000, host: 3000以及vagrant的ID信息;
8. 打开SecureCRTPortable # 主机名为127.0.0.1,填写端口,账户密码等相关信息;
9. Install Git with Apt-Get command:sudo apt-get install git-core;
10. sudo apt-get update;
11. 使用cmd 到D:develoment/Freetalks/ 运行 vagrant reload(`重启`);


# git 相关的命令


1. `git init` (初始化一个本地仓库)
2. `git add .` (将所有文件加入到跟踪列表)
3. `git commit -m "write something title" (提交到本地仓库)
4. `git status` (查看git文件哪处发生改动)
5. `git remote add origin git@github.com:github账户名/github创建的库.git`(将本地仓库关联到github上远程仓库)
6. `git push -u origin master` (将本地仓库的所有内容推送到远程库上，下一次推送时命令去掉 `-u`)


