So, the question is, the world's biggest LAN has been built in China, a misterious country.

Today, I'm gonna show you how to deploy SSR Server to bypass the GFW.

- First, install SSR Server.

```
wget --no-check-certificate https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocksR.sh
chmod +x shadowsocksR.sh
./shadowsocksR.sh 2>&1 | tee shadowsocksR.log
```

- Second, install BBR to speed up the server.

```
wget --no-check-certificate https://github.com/teddysun/across/raw/master/bbr.sh
chmod +x bbr.sh
./bbr.sh
```
