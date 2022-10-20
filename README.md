# bt
btpjb
##

Ubuntu/Deepin全新安装命令：
wget https://github.com/cfwarp/bt/raw/main/install.sh && sudo bash install.sh

Centos全新安装命令： 升级后可能需要重启面板
yum install -y wget && wget -O install.sh  https://github.com/cfwarp/bt/raw/main/install_6.0.sh && sh install.sh

Debian全新安装命令：
wget -O install.sh  https://github.com/cfwarp/bt/raw/main//install-ubuntu_6.0.sh && bash install.sh

升级代码/修复面板：已经安装官方面板，执行下列命令升级到7.6.0PJ版：
curl  https://github.com/cfwarp/bt/raw/main/update6.sh|bash

其他非官方版本7.4.5至7.6.0版本之间所有版本均可，执行下列命令升级到7.6.0PJ版：
curl  https://github.com/cfwarp/bt/raw/main/update6.sh|bash

任意非官方版本还原到官方最新版：
curl http://download.bt.cn/install/update6.sh|bash
