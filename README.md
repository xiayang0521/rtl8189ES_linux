# rtl8189ES_linux
git clone https://github.com/xiayang0521/rtl8189ES_linux.git
cd rtl8189ES_linux.git
git checkout -B rtl8189fs origin/rtl8189fs
make -j4 ARCH=arm CROSS_COMPILE=arm-linux-gnu- KSRC=../linux
