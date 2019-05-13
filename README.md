# 看HBO直播

- HBO中文直播 + 100多个电视台（N个高清台）

## 怎么看？

- 用浏览器打开 iptv.html
- 或者直接去 <http://hbo.epub.fun/>
- 必须用手机号注册后才能看
  - 因为测试过，多ip访问服务端系统会更改token，所以只能是每个人用自己的账号观看

## 账号登录错误？

- 使用一段时间后可能会出现这种情况
  - IP地址被监控了, 服务端已经删除你的账号，即使你重新注册账号也会马上被删，或者干脆已经把你的IP加入防火墙了无法再访问。

## 其它

- promise based
- 默认如果没有本地频道（channels.json）,会请求远程服务器频道
- 不支持IE浏览器
- 支持画中画
- 仅作为宽带测试用

---

## iptv.sh 勿用

- 一键管理脚本 mpegts 转 hls

``` bash
bash -c "$(wget --no-check-certificate -qO- https://raw.githubusercontent.com/woniuzfb/iptv/master/iptv.sh)"
```