# rtl8723bs-Ubuntu16.04

sudo apt-get install git build-essential

git clone 
cd rtl8723bs 
sudo make 
sudo make install 
sudo depmod -a 
sudo modprobe r8723bs 
sudo modinfo r8723bs
