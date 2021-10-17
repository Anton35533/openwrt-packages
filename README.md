

PassWall
[xiaorouji新库地址](https://github.com/xiaorouji/openwrt-passwall.git) 已经自带依赖了
 


1、 lede/package$下运行


```bash
 git clone https://github.com/Anton35533/openwrt-packages.git
```

 2、 或者添加下面代码到lede源码根目录feeds.conf.default文件
 
```bash
 src-git kenzo https://github.com/Anton35533/openwrt-packages


- openwrt 固件编译自定义主题与软件
- luci-theme-ifit          ------------------透明主题（适配18.06修复主机名错误）
- luci-theme-atmaterial_new  ------------------atmaterial 三合一主题（适配18.06）     
- luci-app-smartdns        ------------------smartdns防污染
- luci-app-passwall        ------------------Lienol大神 
- luci-theme-argon_new     ------------------二合蓝 紫主题
- luci-app-ssr-plus        ------------------Lean大神 
- luci-theme-opentomcat    ------------------修复主机名错误（适配18.06）  
- luci-theme-opentomato    ------------------修复主机名错误（适配18.06）
- luci-app-ddnsto          ------------------ddnsto内网穿透


