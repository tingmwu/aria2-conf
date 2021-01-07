# windows下的aria2配置
# 1 下载aria2软件包
[下载链接](https://github.com/aria2/aria2/releases/tag/release-1.35.0)
# 2 下载aria2配置文件包
[下载链接](https://github.com/P3TERX/aria2.conf)
# 3 修改配置文件
```
1.windows下打开 c:/users/%username% 文件夹(%username%为当前用户名)
2.新建.aria2文件夹
3.将aria2配置包中的aria2.conf复制到.aria2文件夹
4. 打开aria2.conf,将/root/.aria2 用c:/users/%username%/.aria2替换
5. 其它配置可自行修改。
```


# aria2常用命令
> --header "cookie: "	添加cookie或者其它头

> --all-proxy=127.0.0.1:7890	设置代理（也可用https-proxy, http-proxy可在帮助文档查看）

> -d 设置下载目录

> -S 查看种子信息

> --select-file=1-2,3  选择下载种子部分文件
