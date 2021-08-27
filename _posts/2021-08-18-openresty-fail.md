#### brew install openresty/brew/openresty

报如下错误

```
fatal: unable to access 'https://github.com/openresty/homebrew-brew/': LibreSSL SSL_connect: SSL_ERROR_SYSCALL in connection to github.com:443
```

解决方案

```
git config --global --unset http.proxy 
git config --global --unset https.proxy
```
