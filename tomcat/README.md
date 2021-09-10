## Tomcat
原镜像地址：https://hub.docker.com/_/tomcat

---

### 镜像说明
移除了 webapps 下的内容，便于 war 包直接部署到 ROOT 目录

---

## 使用此镜像

镜像地址：https://hub.docker.com/r/xunki/tomcat

```
docker run -it --rm --name gfk -p 8017:8080 -v /app/gfk-1.0-SNAPSHOT.war:/usr/local/tomcat/webapps/ROOT.war xunki/tomcat:7-jre8-slim
```
