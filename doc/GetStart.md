# lua
- [http://www.lua.org/](http://www.lua.org/)
### 安装
```bash
curl -R -O http://www.lua.org/ftp/lua-5.4.4.tar.gz
tar zxf lua-5.4.4.tar.gz
cd lua-5.4.4
make all test
```

# lua 的包管理工具 luarocks
- [https://luarocks.org/#quick-start](https://luarocks.org/#quick-start)
### 安装
```bash
$ wget https://luarocks.org/releases/luarocks-3.9.1.tar.gz
$ tar zxpf luarocks-3.9.1.tar.gz
$ cd luarocks-3.9.1
$ ./configure && make && sudo make install
```

### 安装一个 `luasocket` 模块
```bash
sudo luarocks install luasocket
```
会被安装到 `luarocks/lua_modules` 目录下。