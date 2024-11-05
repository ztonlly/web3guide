## VPS自建节点推荐
+ **Github**：[https://github.com/mack-a/v2ray-agent](https://github.com/mack-a/v2ray-agent)
+ **描述**：八合一共存脚本
+ **支持核心**: Xray-core、sing-box 
+ **支持协议**:
    + VLESS(Reality、Vision(TCP)、WS、gRPC、SplitHTTP)
    + VMess(TCP、WS、HTTPUpgrade)
    + Trojan(TCP、gRPC)
    + Hysteria2(sing-box)
    + Tuic(sing-box)
    + NaiveProxy(sing-box)


## Cloudflare自建节点信息
```部署worker.js代码，更改UUID和选择反代域名，配置客户端IP和端口```

### **在线生成UUID**：[https://1024tools.com/uuid](https://1024tools.com/uuid)
### **在线优选IP**：[https://stock.hostmonit.com/Cloudflareyes](https://stock.hostmonit.com/Cloudflareyes)

### cloudflare运行模式：
+ vless+ws可任意选择端口：80、8080、8880、2052、2082、2086、2095
+ vless+ws+tls可任意选择端口：443、8443、2053、2083、2087、2096

### cloudflare反代域名:
+ cdn-all.xn--b6gac.eu.org
+ cdn.xn--b6gac.eu.org
+ cdn-b100.xn--b6gac.eu.org
+ edgetunnel.anycast.eu.org
+ cdn.anycast.eu.org

### 【Cloudflare】节点信息
```bash
vless://11dc55cc-2938-40a5-bb23-33a87a9de6f7@172.67.237.97:2095?security=&sni=vless.ztonlly.workers.dev&fp=randomized&type=ws&path=/?ed%3D2048&host=vless.ztonlly.workers.dev&encryption=none#vless.ztonlly.workers.dev
```
