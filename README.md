# Vagrant����



1. ��װvagrant[����](https://www.vagrantup.com/downloads.html),virtualbox,SecureCRTP[����](http://download.pchome.net/internet/telnet/download-54.html);
2. ��װvagrant��virtualBox;
3. ���������뿪������Ŀ¼;
4. [����](http://www.vagrantbox.es/)boxѡ��͵�İ汾--Ubuntu lucid 32;
5. ���box `vagrant box add base` + Զ�˵�box��ַ���߱��ص�box�ļ���,�����ص�����������ٶȻ�ȽϿ�;
6. vagrant init;
7. vagrant up # ��������,��дvagrantfile�����config. vm.network :forwarded_port, guest: 3000, host: 3000�Լ�vagrant��ID��Ϣ;
8. ��SecureCRTPortable # �½�Sessions ������Ϊ127.0.0.1,��д�˿�2222,�˻�����������Ϣ;
9. sudo apt-get update;
10. Install Git with Apt-Get command:sudo apt-get install git-core;

11. ʹ��cmd ��D:develoment/Freetalks/ ���� vagrant reload(`����`);

# Vagrant �������



1. `vagrant up` ����
2. `vagrant halt` �ػ�
3. `vagrant reload` ����


# Vagrant ʹ��


1. cd /vagrant ���ص��������װĿ¼��


# git ��ص�����


1. `git init` (��ʼ��һ�����زֿ�)
2. `git add .` (�������ļ����뵽�����б�)
3. `git commit -m "write something title" (�ύ�����زֿ�)
4. `git status` (�鿴git�ļ��Ĵ������Ķ�)
5. `git remote add origin git@github.com:github�˻���/github�����Ŀ�.git`(�����زֿ������github��Զ�ֿ̲�)
6. `git push -u origin master` (�����زֿ�������������͵�Զ�̿��ϣ���һ������ʱֱ�� `git push`)






