# 自用 TVBox 接口 & m3u 直播源整理

所有内容为互联网收集，只为自用...

### m3u

https://zb.v1.mk/

https://github.com/youshandefeiyang/IPTV

https://github.com/YanG-1989/m3u

https://github.com/fanmingming/live

### TVBox 接口

https://github.com/liu673cn/box

---

## 挑选后的自用地址

## [Github 静态加速](https://github.abskoop.workers.dev/)

### 直播源(m3u)

https://cdn.jsdelivr.net/gh/jyoketsu/tv@main/live.m3u

### 直播源(通用格式)

https://cdn.jsdelivr.net/gh/jyoketsu/tv@main/live.txt

### TVBox 接口

https://cdn.jsdelivr.net/gh/jyoketsu/tv@main/m.json

## [直播源列表格式转换](https://guihet.com/tvlistconvert.html)

## [在线加密解密](https://tool.oschina.net/encrypt?type=3)

## TVBox 直播源

```
"lives": [{"group": "redirect","channels": [{"name": "redirect","urls": [
"proxy://do=live&type=txt&ext=aHR0cHM6Ly9jZG4uanNkZWxpdnIubmV0L2doL2p5b2tldHN1L3R2QG1haW4vbGl2ZS50eHQ="
]}]}],
```

## jsDelivr CDN的使用及缓存刷新
将想刷新的链接的开头的cdn 更改为 purge，访问这个接口，返回status: ok，就代表缓存刷新了。
