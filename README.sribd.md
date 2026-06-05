# 笔记

## 构建

这里我们只构建 easyconnect 7.6.7 版本，命令如下：

```bash
docker build -t docker.io/hagb/docker-easyconnect:7.6.7.$(date -uI) $(cat build-args/7.6.7-amd64.txt) .
```
