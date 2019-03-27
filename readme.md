## 功能说明
    内网穿透

## 服务器端部署

```
docker run -d --name=frps --restart=always --expose=80 -p 7000:7000 -p 7500:7500 -e VIRTUAL_HOST=*.frp.ngapp.net zhaishuaigan/frps
```

## 客户端使用:  
    https://github.com/fatedier/frp/blob/master/README_zh.md