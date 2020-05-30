### 安装/更新方式（h2 和 ws 版本已合并）
Vmess+websocket+TLS+Nginx+Website
```
wget -N --no-check-certificate -q -O install.sh "https://raw.githubusercontent.com/wenge110110/v2ray/master/install.sh" && chmod +x install.sh && bash install.sh
```



### 启动方式

启动 V2ray：`systemctl start v2ray`

停止 V2ray：`systemctl stop v2ray`

启动 Nginx：`systemctl start nginx`

停止 Nginx：`systemctl stop nginx`

### 相关目录

Web 目录：`/home/wwwroot/3DCEList`

V2ray 服务端配置：`/etc/v2ray/config.json`

V2ray 客户端配置: `~/v2ray_info.inf`

Nginx 目录： `/etc/nginx`

证书文件: `/data/v2ray.key 和 /data/v2ray.crt` 请注意证书权限设置


𝒘𝒖𝒍𝒂𝒃𝒊𝒏𝒈 邀请您使用麻瓜宝，基于Telegram的电子钱包，匿名支付0手续费秒级到账。https://telegram.me/MugglePayBot?start=T3Y78AZ3

您可以通过Telegram向我匿名捐赠：发送 /pay @wulabing xxx  到 @MugglePayBot 即可 默认货币为 USDT 

如需要通过支付宝/微信捐赠，请Telegram私聊 @wulabing 感谢您的支持


