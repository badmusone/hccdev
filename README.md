# linux ubuntu 14.04

sudo locale-gen en_US.UTF-8 zh_CN.UTF-8 zh_TW.UTF-8   //local setting
sudo dpkg-reconfigure locales   //local setting


sudo apt-get install ntp unzip git build-essential libssl-dev libdb-dev libdb++-dev libboost-all-dev  //install coin compilator dependencies

sudo apt-get install libqrencode-dev aptitude   //install coin compilator dependencies


sudo aptitude install miniupnpc libminiupnpc-dev  //install coin compilator dependencies

git clone https://github.com/hccdev/hccdev.git 

chmod 755 build_detect_platform

make libleveldb.a libmemenv.a
