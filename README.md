# update-ipv6-hosts-and-generate-proxy-whitelist
更新ipv6的hosts并根据hosts中的域名生成一份用于AutoProxy插件的白名单

经测试，生成的白名单由于数量庞大，且有一定的重复性，效率不是很高，故[新作PAC脚本](https://github.com/autulin/update-ipv6-hosts-and-generate-proxy-whitelist/blob/master/bupt-ipv6.pac)，修改于[mono_pac](https://github.com/blackgear/mono_pac)
