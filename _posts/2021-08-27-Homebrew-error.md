**MacOS系统使用 Homebrew 官方地址时，报错：**
```
Mac：/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

curl: (35) LibreSSL SSL_connect: SSL_ERROR_SYSCALL in connection to raw.githubusercontent.com:443 
```
** 解决办法：**
使用国内源

```
/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)"
```
该地址提供多个国内源地址，选择一个安装即可
**查检安装结果**
```
brew -v
```
