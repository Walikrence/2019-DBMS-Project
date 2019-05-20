PMDK以及依赖包安装
```sh
apt install autoconf -y
apt install pkg-config -y
apt install libndctl-dev -y
apt install libdaxctl-dev -y
git clone https://github.com/pmem/pmdk.git
make
make install
```