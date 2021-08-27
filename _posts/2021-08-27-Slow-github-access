#### macOS解决方法
1. 打开hosts文件.终端输入sudo vi /etc/hosts
2. 在 vim 编辑中，输入i可以编辑hosts文件(如果按了没效果再按一下enter)
3. 可以直接粘贴下面地址和域名的映射关系到hosts的最后一行
```
140.82.112.4 https://github.com
```
如果觉得vim编辑命令不熟悉,可以直接进入文件修改

在文件 => 前往 => 前往文件夹(快捷键:Command+Shift+G) => 输入/etc/hosts => 找到 hosts 文件打开 => 粘贴上面内容即可

4. 刷新DNS缓存
```
dscacheutil -flushcache
```

**备注：上面的映射关系怎么来的 ？**

> 查询域名对应的 IP 地址[https://www.ipaddress.com/]
> 当你看到这篇文章的时候映射关系已经变了，所以在写 hosts 文件之前建议查一下最新的映射关系
