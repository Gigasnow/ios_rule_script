# Global

## 前言

本项目的Global分流规则由爬虫程序自动维护。

定时爬取互联网上开源的Global分流规则，将其进行清洗、去重、合并、优化后，形成单一的分流规则文件，旨在解决引用大量外部规则造成规则重复的问题。



最后检查时间：2021-03-10 11:49:16.194342。

## 规则统计

总计规则：28716 条。

各类型规则统计：

| 类型 | 数量(条) |
| ---- | ---- |
| DOMAIN-SUFFIX | 28504 |
| DOMAIN | 39 |
| DOMAIN-KEYWORD | 42 |
| IP-CIDR | 127 |
| IP-CIDR6 | 3 |
| PROCESS-NAME | 1 |
## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### Clash 
实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global.yaml

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Domain.yaml

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Clash/Global/Global.yaml

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Clash/Global/Global_Domain.yaml

如果稳定版无法访问 ，可能是尚未从实时版的分支合并，建议您先使用实时版，或等待下次稳定版分支合并。

## 重复统计

当前分流规则，已包含以下子规则：

- Proxy

除非特殊需求，否则不建议重复引用。


当前分流规则，与本项目其他分流规则重复情况统计(点击重复数量可查看明细)。



| 名称 | 数量 | 重复 | 重合度 |
| ---- | ---- | ---- | ------ |
|  [9to5](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/9to5)    | 7   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [ATTWatchTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/ATTWatchTV)    | 6   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Atlassian](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Atlassian)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [CNN](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/CNN)    | 6   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Comodo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Comodo)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [DigiCert](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/DigiCert)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Espn](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Espn)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Jwplayer](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Jwplayer)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [KKBOX](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/KKBOX)    | 7   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Picsee](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Picsee)    | 6   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Sectigo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Sectigo)    | 7   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Shopify](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Shopify)    | 8   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Slack](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Slack)    | 8   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Sling](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Sling)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Snap](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Snap)    | 6   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Spark](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Spark)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Stackexchange](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Stackexchange)    | 15   | [15](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [VK](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/VK)    | 7   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Voxmedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Voxmedia)    | 16   | [16](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [WIX](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/WIX)    | 9   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Wikimedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Wikimedia)    | 20   | [20](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Wikipedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Wikipedia)    | 12   | [12](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Wordpress](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Wordpress)    | 8   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Zendesk](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Zendesk)    | 6   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Proxy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Proxy)    | 28670   | [28584](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   99.7% |
|  [BlackList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/BlackList)    | 771   | [757](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   98.18% |
|  [VOA](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/VOA)    | 51   | [49](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   96.08% |
|  [Developer](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Developer)    | 24   | [23](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   95.83% |
|  [DtDNS](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/DtDNS)    | 17   | [16](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   94.12% |
|  [Vimeo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Vimeo)    | 16   | [15](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   93.75% |
|  [Twitter](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Twitter)    | 26   | [24](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   92.31% |
|  [EA](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/EA)    | 163   | [150](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   92.02% |
|  [Adobe](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Adobe)    | 138   | [126](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   91.3% |
|  [Bloomberg](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Bloomberg)    | 22   | [20](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   90.91% |
|  [Line](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Line)    | 22   | [20](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   90.91% |
|  [Discord](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Discord)    | 10   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   90.0% |
|  [PayPal](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/PayPal)    | 247   | [221](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   89.47% |
|  [Dell](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Dell)    | 117   | [104](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   88.89% |
|  [Fox](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Fox)    | 256   | [227](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   88.67% |
|  [Dropbox](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Dropbox)    | 17   | [15](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   88.24% |
|  [HuluUSA](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/HuluUSA)    | 51   | [45](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   88.24% |
|  [DynDNS](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/DynDNS)    | 8   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   87.5% |
|  [KakaoTalk](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/KakaoTalk)    | 14   | [12](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   85.71% |
|  [Hulu](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Hulu)    | 56   | [47](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   83.93% |
|  [Riot](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Riot)    | 54   | [45](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   83.33% |
|  [Gucci](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Gucci)    | 6   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   83.33% |
|  [Xbox](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Xbox)    | 35   | [29](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   82.86% |
|  [Github](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Github)    | 23   | [19](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   82.61% |
|  [Zee](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Zee)    | 22   | [18](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   81.82% |
|  [Bestbuy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Bestbuy)    | 82   | [66](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   80.49% |
|  [Facebook](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Facebook)    | 68   | [54](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   79.41% |
|  [Spotify](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Spotify)    | 19   | [15](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   78.95% |
|  [BrightCove](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/BrightCove)    | 14   | [11](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   78.57% |
|  [ZeeTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/ZeeTV)    | 9   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   77.78% |
|  [Cisco](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Cisco)    | 118   | [91](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   77.12% |
|  [AppleDaily](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/AppleDaily)    | 13   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   76.92% |
|  [IBM](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/IBM)    | 13   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   76.92% |
|  [Samsung](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Samsung)    | 13   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   76.92% |
|  [Nintendo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Nintendo)    | 123   | [94](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   76.42% |
|  [CBS](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/CBS)    | 29   | [22](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   75.86% |
|  [SmarTone](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/SmarTone)    | 15   | [11](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   73.33% |
|  [Vercel](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Vercel)    | 15   | [11](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   73.33% |
|  [PCCW](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/PCCW)    | 25   | [18](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   72.0% |
|  [Scholar](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Scholar)    | 177   | [127](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   71.75% |
|  [Google](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Google)    | 108   | [76](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   70.37% |
|  [Zoho](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Zoho)    | 13   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   69.23% |
|  [NYTimes](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/NYTimes)    | 16   | [11](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   68.75% |
|  [Game](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Game)    | 532   | [356](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   66.92% |
|  [AbemaTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/AbemaTV)    | 21   | [14](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   66.67% |
|  [Logitech](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Logitech)    | 9   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   66.67% |
|  [Manorama](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Manorama)    | 12   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   66.67% |
|  [Mozilla](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Mozilla)    | 18   | [12](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   66.67% |
|  [Pixnet](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Pixnet)    | 9   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   66.67% |
|  [Whatsapp](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Whatsapp)    | 21   | [14](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   66.67% |
|  [Netflix](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Netflix)    | 41   | [27](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   65.85% |
|  [Pinterest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Pinterest)    | 23   | [15](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   65.22% |
|  [Nike](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Nike)    | 11   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   63.64% |
|  [Qualcomm](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Qualcomm)    | 44   | [28](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   63.64% |
|  [Telegram](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Telegram)    | 30   | [19](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   63.33% |
|  [Disney](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Disney)    | 131   | [82](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   62.6% |
|  [Rarbg](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Rarbg)    | 16   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   62.5% |
|  [Amazon](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Amazon)    | 166   | [103](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   62.05% |
|  [Microsoft](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Microsoft)    | 98   | [60](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   61.22% |
|  [iCloud](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/iCloud)    | 51   | [31](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   60.78% |
|  [AmazonPrimeVideo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/AmazonPrimeVideo)    | 24   | [14](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   58.33% |
|  [Duckduckgo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Duckduckgo)    | 43   | [25](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   58.14% |
|  [Niconico](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Niconico)    | 9   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   55.56% |
|  [Shopee](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Shopee)    | 11   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   54.55% |
|  [TikTok](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/TikTok)    | 15   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   53.33% |
|  [BBC](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/BBC)    | 21   | [11](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   52.38% |
|  [HBOHK](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/HBOHK)    | 14   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   50.0% |
|  [Cloudflare](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Cloudflare)    | 41   | [20](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   48.78% |
|  [BMW](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/BMW)    | 729   | [354](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   48.56% |
|  [Intel](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Intel)    | 263   | [126](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   47.91% |
|  [Dailymail](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Dailymail)    | 17   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   47.06% |
|  [OneDrive](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/OneDrive)    | 17   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   47.06% |
|  [Apple](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Apple)    | 95   | [43](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   45.26% |
|  [Oracle](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Oracle)    | 25   | [11](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   44.0% |
|  [HBO](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/HBO)    | 30   | [13](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   43.33% |
|  [Naver](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Naver)    | 51   | [21](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   41.18% |
|  [Garena](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Garena)    | 15   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   40.0% |
|  [Verizon](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Verizon)    | 182   | [71](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   39.01% |
|  [DAZN](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/DAZN)    | 18   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   38.89% |
|  [Globalsign](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Globalsign)    | 13   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   38.46% |
|  [Sony](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Sony)    | 116   | [43](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   37.07% |
|  [TVB](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/TVB)    | 19   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   36.84% |
|  [Verisign](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Verisign)    | 33   | [12](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   36.36% |
|  [Huffpost](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Huffpost)    | 18   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   33.33% |
|  [Twitch](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Twitch)    | 18   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   33.33% |
|  [ThomsonReuters](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/ThomsonReuters)    | 31   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   32.26% |
|  [YouTube](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/YouTube)    | 177   | [57](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   32.2% |
|  [eBay](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/eBay)    | 44   | [14](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   31.82% |
|  [Canon](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Canon)    | 70   | [22](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   31.43% |
|  [Westerndigital](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Westerndigital)    | 23   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   30.43% |
|  [Starbucks](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Starbucks)    | 32   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   28.12% |
|  [McDonalds](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/McDonalds)    | 26   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   26.92% |
|  [Gettyimages](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Gettyimages)    | 25   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   24.0% |
|  [Blizzard](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Blizzard)    | 61   | [14](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   22.95% |
|  [VISA](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/VISA)    | 99   | [21](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   21.21% |
### 特别说明
程序在实际运算时，会根据DOMAIN、DOMAIN-SUFFIX、IP-CIDR、IP-CIDR6间的包含关系进行去重，而出于运行效率考虑，重复规则只统计纯文本匹配，所以可能与实际效果有所出入，仅供参考。

## 数据来源

本项目的Global分流规则的数据来自以下链接，通常已涵盖所有数据来源的分流规则。如果你正在使用这些分流规则，建议不要与本项目的Global分流规则混合使用，以免造成规则重复。

- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ProxyGFWlist.list
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ProxyLite.list
- https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/Ruleset/Global.list
- https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/Ruleset/GlobalMedia.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Global.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Global.list
- https://raw.githubusercontent.com/GeQ1an/Rules/master/QuantumultX/Filter/Outside.list
- https://raw.githubusercontent.com/Hackl0us/SS-Rule-Snippet/master/Rulesets/Surge/Basic/Apple-proxy.list
- https://raw.githubusercontent.com/Loyalsoldier/surge-rules/release/ruleset/gfw.txt
- https://raw.githubusercontent.com/Loyalsoldier/surge-rules/release/ruleset/greatfire.txt
- https://raw.githubusercontent.com/Loyalsoldier/surge-rules/release/ruleset/proxy.txt
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/BlackList/BlackList.list
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/Proxy/Proxy.list
- https://raw.githubusercontent.com/eHpo1/Rules/master/Surge4/Ruleset/Global.list
- https://raw.githubusercontent.com/lhie1/Rules/master/Surge/Surge%203/Provider/Proxy.list
- https://raw.githubusercontent.com/sve1r/Rules-For-Quantumult-X/develop/Rules/Region/Global.list


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

欢迎通过[issues](https://github.com/blackmatrix7/ios_rule_script/issues/new)提交反馈，共同完善本项目的Global分流规则。

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