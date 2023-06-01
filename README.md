# tools

## HTTTP SERVER
赋予普通用户80端口使用权限
```shell
sudo setcap cap_net_bind_service=+ep /usr/bin/python3.10
```

