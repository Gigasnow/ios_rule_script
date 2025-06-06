# 游戏

## 前言

本项目的游戏分流规则由爬虫程序自动维护。

定时爬取互联网上开源的游戏分流规则，将其进行清洗、去重、合并、优化后，形成单一的分流规则文件，旨在解决引用大量外部规则造成规则重复的问题。



最后检查时间：2021-03-10 11:49:26.737270。

## 规则统计

总计规则：532 条。

各类型规则统计：

| 类型 | 数量(条) |
| ---- | ---- |
| DOMAIN-SUFFIX | 483 |
| IP-CIDR | 45 |
| DOMAIN-KEYWORD | 4 |
## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### Shadowrocket 
实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game.list

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Shadowrocket/Game/Game.list

## 重复统计

当前分流规则，已包含以下子规则：

- Battle

- Blizzard

- Classic

- Diablo-III

- EA

- Epic

- Garena

- Gog

- Hearthstone

- Heroes-of-the-Storm

- Nintendo

- OP

- Overwatch

- PlayStation

- Purikonejp

- Riot

- Rockstar

- StarCraft-II

- Steam

- SteamCN

- Supercell

- UBI

- WildRift

- World-of-Warcraft

- Xbox

除非特殊需求，否则不建议重复引用。


当前分流规则，与本项目其他分流规则重复情况统计(点击重复数量可查看明细)。



| 名称 | 数量 | 重复 | 重合度 |
| ---- | ---- | ---- | ------ |
|  [Diablo-III](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Diablo-III)    | 7   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   100.0% |
|  [Heroes-of-the-Storm](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Heroes-of-the-Storm)    | 9   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   100.0% |
|  [Overwatch](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Overwatch)    | 7   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   100.0% |
|  [StarCraft-II](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/StarCraft-II)    | 8   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   100.0% |
|  [World-of-Warcraft](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/World-of-Warcraft)    | 8   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   100.0% |
|  [Blizzard](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Blizzard)    | 61   | [61](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   100.0% |
|  [EA](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/EA)    | 163   | [163](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   100.0% |
|  [Steam](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Steam)    | 32   | [32](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   100.0% |
|  [Rockstar](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Rockstar)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   100.0% |
|  [SteamCN](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/SteamCN)    | 14   | [14](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   100.0% |
|  [Supercell](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Supercell)    | 24   | [24](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   100.0% |
|  [Garena](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Garena)    | 15   | [15](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   100.0% |
|  [Nintendo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Nintendo)    | 123   | [123](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   100.0% |
|  [Riot](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Riot)    | 54   | [54](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   100.0% |
|  [UBI](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/UBI)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   100.0% |
|  [Xbox](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Xbox)    | 35   | [35](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   100.0% |
### 特别说明
程序在实际运算时，会根据DOMAIN、DOMAIN-SUFFIX、IP-CIDR、IP-CIDR6间的包含关系进行去重，而出于运行效率考虑，重复规则只统计纯文本匹配，所以可能与实际效果有所出入，仅供参考。

## 数据来源

本项目的游戏分流规则的数据来自以下链接，通常已涵盖所有数据来源的分流规则。如果你正在使用这些分流规则，建议不要与本项目的游戏分流规则混合使用，以免造成规则重复。

- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Steam.list
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/SteamCN.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Extra/Game/Supercell.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Extra/Game/WildRift.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Game/Blizzard.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Game/Blizzard/Battle.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Game/Blizzard/Classic.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Game/Blizzard/Diablo-III.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Game/Blizzard/Hearthstone.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Game/Blizzard/Heroes-of-the-Storm.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Game/Blizzard/Overwatch.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Game/Blizzard/StarCraft-II.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Game/Blizzard/World-of-Warcraft.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Game/Steam.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/Game/Blizzard.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/Game/EA.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/Game/Garena.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/Game/Gog.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/Game/Nintendo.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/Game/OP.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/Game/PlayStation.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/Game/Purikonejp.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/Game/Riot.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/Game/Rockstar.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/Game/Steam.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/Game/UBI.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/Game/Xbox.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/PROXY/Garena.list
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/PlayStation/PlayStation.list
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/Rockstar/Rockstar.list
- https://raw.githubusercontent.com/lhie1/Rules/master/Surge/Surge%203/Provider/Steam.list
- https://raw.githubusercontent.com/sve1r/Rules-For-Quantumult-X/develop/Rules/Games/Epic.list
- https://raw.githubusercontent.com/sve1r/Rules-For-Quantumult-X/develop/Rules/Games/GamesAll.list
- https://raw.githubusercontent.com/sve1r/Rules-For-Quantumult-X/develop/Rules/Games/WildRift.list


感谢以上分流规则作者的辛勤付出（排名不分先后）。

如果您有更好的分流规则，欢迎提交给我，我会将它加到数据源中继续完善。

## 程序特点

### 断链处理

对于某些已删除或失效的数据源，继续使用本地缓存的文件，减少因为断链造成的影响。

### 规则过滤

通过关键字、正则、模糊匹配三种方式对规则进行过滤，以移除部分数据源中的错误规则。

### 合并去重

不仅对完全相同的规则进行去重，还会根据DOMAIN、DOMAIN-SUFFIX、IP-CIDR、IP-CIDR6等规则间的包含关系进行合并去重。

### 域名解析

对DOMAIN类型的规则进行DNS解析记录查询，丢弃连续多次无法解析的域名。

### 正则合并

通过程序对相似正则进行合并，不定时手动核验正则合并结果。

### 正则推导

通过程序对含有正则的规则，推导需要MITM的主机名，不定时手动核验推导结果。

### 正则编译

通过程序对正则类型的规则进行编译，去除无法通过编译的正则。

## 最后

### 完善规则

如果您：

1. 有更优的原始规则数据
2. 有更多的黑名单规则数据
3. 有更好的优化建议
4. 在使用分流规则时出现异常
5. 有其他问题

欢迎通过[issues](https://github.com/blackmatrix7/ios_rule_script/issues/new)提交反馈，共同完善本项目的游戏分流规则。

感谢

[@fiiir](https://github.com/fiiir) [@Tartarus2014](https://github.com/Tartarus2014) [@zjcfynn](https://github.com/zjcfynn) [@chenyiping1995](https://github.com/chenyiping1995) 

提供规则数据源及改进建议

### 其他问题

爬虫开发的初衷是为满足自己几方面需求：

1. 去除混用多个去广告规则造成的重复
2. 去除多个去广告规则中某些规则
3. 多个分流规则间重复情况检查
4. 定时同步数据源更新

本项目的分流规则还是以自用为主，请不要对外宣传此分流规则。所以，还是请低调使用吧。