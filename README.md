## ngrok Docker镜像

## 申请泛解析域名证书
[申请免费泛解析域名](https://lizhijun.me/12ff76ca13cb4995898d61a7bcc6ad58)

### 拷贝ssl证书
```
chain.pem(第一段----BEGIN CERTIFICATE---—) > rootCa.pem
cert.pem > server.crt
privkey.pem > server.key
```


#### docker-compose 方式启动

- 构建镜像启动

```bash
docker-compose up --build -d
```

- 停止容器

```bash
docker-compose down
```




