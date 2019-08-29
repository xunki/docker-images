## Sentinel: 分布式系统的流量防卫兵
项目地址：https://github.com/alibaba/Sentinel

---

### 控制台 wiki
https://github.com/alibaba/Sentinel/wiki/%E6%8E%A7%E5%88%B6%E5%8F%B0

---

## 使用此镜像

镜像地址：https://hub.docker.com/r/xunki/sentinel-dashboard

```
docker run -it --rm -p 8080:8080 -e sentinel.dashboard.autoRemoveMachineMillis=300000 -e sentinel.dashboard.auth.username=sentinel -e sentinel.dashboard.auth.password=sentinel xunki/sentinel-dashboard
```

可选参数请查阅 [控制台功能介绍](https://github.com/alibaba/Sentinel/blob/master/sentinel-dashboard/Sentinel_Dashboard_Feature.md)
