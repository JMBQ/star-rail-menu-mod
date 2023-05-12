# star-rail-menu-mod

这游戏存在dex校验，没有签名校验，没有TP保护，菜单mod很轻松就弄出来了   

但真正棘手的是它的战斗校验机制，它不校验text的crc32，而是校验战斗中产生的数据，用fixpoint结构体来保护隐藏   

我暂时绕过了战斗作弊校验，但它居然没有上传结果，看来我还需要花些时间来追踪它

release等我搞定了校验再放，又或者随便增放个加速功能先丢出来？

https://github.com/JMBQ/star-rail-menu-mod/assets/78288131/b3c84d44-411f-4b2e-92e5-613de95ba274

