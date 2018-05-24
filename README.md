# ssrmubackup with BBR(able to use independently!)
# 仅个人备份使用，以应对可能出现的原作者（逗比根据地博主）受不可抗力删除项目的情况。

# Debian 7 x64 required (linux)
# install way 1
wget -N --no-check-certificate https://raw.githubusercontent.com/Ache1123/ssrmubackup/master/ssrmu.sh && chmod +x ssrmu.sh && bash ssrmu.sh
# install way 2
apt-get update   
apt-get install git -y   
git clone https://github.com/Ache1123/ssrmubackup   
cd ssrmubackup     
chmod +x ssrmu.sh    
./ssrmu.sh local   
