# rtl8189ES_linux
RTL8189ES / RTL8189ETV
Driver has its own repository:

git clone https://github.com/jwrdegoede/rtl8189ES_linux.git
cd rtl8189ES_linux.git
make -j4 ARCH=arm CROSS_COMPILE=arm-linux-gnu- KSRC=../linux

RTL8189FTV
Driver has its own repository:

git clone https://github.com/jwrdegoede/rtl8189ES_linux.git
cd rtl8189ES_linux.git
git checkout -B rtl8189fs origin/rtl8189fs
make -j4 ARCH=arm CROSS_COMPILE=arm-linux-gnu- KSRC=../linux

from ----------------------
RTL8189FTV驱动交叉编译
https://blog.csdn.net/u011003120/article/details/90200176
