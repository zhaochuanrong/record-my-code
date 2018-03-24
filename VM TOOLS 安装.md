---
title: VM TOOLS 安装
grammar_cjkRuby: true
---
1、启动CentOS虚拟机


2、创建挂载点目录

mkdir /mnt/cdrom

3、挂载光驱

mount /dev/cdrom /mnt/cdrom

4、查看挂载光驱结果

cd /mnt/cdrom

ls查看/mnt/cdrom路径下的文件信息，发现有一个VMware-Linux-tools.tar.gz文件说明挂在成功

5、解压缩文件到/tmp

tar -zxvf /mnt/cdrom/vmware-linux-tools.tar.gz -C /tmp

6、 进入到解压缩后的目录

cd /tmp/vmware-tools-distrib路径下

7、执行./vmware-install.pl文件

./vmware-install.pl



