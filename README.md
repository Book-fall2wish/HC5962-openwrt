# HC5962-openwrt  
踩坑记录  
因为需要ssr-plus和passwall，在feeds.conf.default中加入：  
src-git helloworld https://github.com/fw876/helloworld  
src-git passwall https://github.com/xiaorouji/openwrt-passwall  
之后执行（-f强制覆盖重复文件）  
./scripts/feeds update -a -f  
./scripts/feeds install -a -f  
