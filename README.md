# Vagrant����


1. ��װvagrant[����](https://www.vagrantup.com/downloads.html),virtualbox,SecureCRTP[����](http://download.pchome.net/internet/telnet/download-54.html)

2. ��װvagrant��virtualBox

3. ���������뿪������Ŀ¼

4. [����](http://www.vagrantbox.es/)boxѡ��͵�İ汾--Ubuntu lucid 32

5. ���box `vagrant box add base` + Զ�˵�box��ַ���߱��ص�box�ļ���,�����ص�����������ٶȻ�ȽϿ�

6. vagrant init

7. vagrant up # ��������,��дvagrantfile�����config. vm.network :forwarded_port, guest: 3000, host: 3000�Լ�vagrant��ID��Ϣ

8. ��SecureCRTPortable # �½�Sessions ������Ϊ127.0.0.1,��д�˿�2222,�˻�����������Ϣ

9. sudo apt-get update

10. Install Git with Apt-Get command:sudo apt-get install git-core

11. ʹ��cmd ��D:develoment/Freetalks/ ���� vagrant reload(`����`)


# Vagrant �������



1. `vagrant up` ����

2. `vagrant halt` �ػ�

3. `vagrant reload` ����


# Vagrant ʹ��


1. cd/����Ŀ¼�������������ȥ��Vagrant init װ��Ŀ¼�²�������

2. cd /vagrant ���ص��������װĿ¼��


# git ��ص�����

1. `git config --global user.name "Your Name"` (��װ��git�������û���������)

2. `git config --global user.email "Your email"` (��������)

3. `ssh-keygen -t rsa -C "youremail@example.com"` (���� SSH key)

4. `ssh-agent -s` (�鿴 ssh �Ƿ�����)

5. `ssh -T git@github.com` (��֤)
 
6. `git init` (��ʼ��һ�����زֿ�)

7. `git add .` (�������ļ����뵽�����б�)

8. `git commit -m "write something title"` (�ύ�����زֿ�)

9. `git status` (�鿴git�ļ��Ĵ������Ķ�)

10. `git remote add origin git@github.com:github�˻���/github�����Ŀ�.git`(�����زֿ������github��Զ�ֿ̲�)

11. `git push -u origin master` (�����زֿ�������������͵�Զ�̿��ϣ���һ������ʱֱ�� `git push`)

12. `git clone URL` (��¡Զ�ֿ̲�)

13. `git branch` (�鿴��ǰ��֧)

14. `git checkout -- filename` (�ļ��ָ������°汾������ʧ���һ���ύ�����޸ĵ�����)

15. `git checkout name` (�л���֧��name Ϊ��֧����)


# vim �������


1. `vim filename` (�򿪱༭�ļ�)

2. ��һ��`i`�� (���б༭�ļ�)

3. ��һ��`Esc`�� (�˳�i(����)���������������ʹ��)

4. `:wq` (�����ļ����˳�)

5. `:q!` (ǿ���˳�,������)

6. `: w filename` (��������ָ�����ļ���filename����)

# ʵ��vistualbox ubuntu ��win7�����ļ����裺

1. ��vistualbox ubuntu ��������Ͻǵ����á����������ļ��С�����ѡ��һ���ڱ����ϵ��ļ���λ�á���������һ���ļ�����

2. ����Ubuntu�ն� ��������������

	sudo mkdir /mnt/share (��mntĿ¼�´���һ��share�ļ���)

	sudo mount -t vboxsf name(���������ļ��е�����) /mnt/share 

3. ʹ��cp����ʵ���ļ��ĸ��ƣ����������ļ����µ�Ŀ¼���Ƶ� /mnt/share,��ʵ���ļ�������win7������Ҳ�ῴ�����ļ�
	cp -r �����ļ��� /mnt/share(�����ļ���λ��)




