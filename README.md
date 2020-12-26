# manjaro-linux-ssh

manjaro-linux-ssh服务配置文件，允许root登录的配置文件

先安装好sshd服务，
sudo pacman -S sshd

再将系统中的sshd_config文件备份

mv /etc/ssh/sshd_config /etc/ssh/sshd_config.bak

然后把此页面中的sshd_config文件下载到/etc/ssh/目录中

重启sshd服务
 systemctl restart sshd.service
