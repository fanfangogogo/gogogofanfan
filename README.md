# gogogofanfan

FanFan want to fly, can you follow me??


Trojan安装脚本,选择好VPS，再对命令少加改动.
sudo apt update
sudo apt -y install wget


支持：centos7+/debian9+/ubuntu16.04+


wget -N --no-check-certificate "https://raw.githubusercontent.com/fanfangogogo/gogogofanfan/main/trojan1.sh" && chmod +x trojan1.sh && ./trojan1.sh



wget -N --no-check-certificate "https://raw.githubusercontent.com/fanfangogogo/gogogofanfan/main/trojan2.sh" && chmod +x trojan2.sh && ./trojan2.sh



wget -N --no-check-certificate "https://raw.githubusercontent.com/fanfangogogo/gogogofanfan/main/trojan3.sh" && chmod +x trojan3.sh && ./trojan3.sh



bbr安装别忘了，加个速

cd /usr/src && wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh

systemctl restart trojan
