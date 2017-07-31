# 配置nginx服务器时 ssl方式conf文件配置

##若为http方式访问

>重写至https 

```
rewrite ^(.*)$  https://$host$1 permanent; 
```


