# GlobalMedia

## 前言

本项目的GlobalMedia分流规则由爬虫程序自动维护。

定时爬取互联网上开源的GlobalMedia分流规则，将其进行清洗、去重、合并、优化后，形成单一的分流规则文件，旨在解决引用大量外部规则造成规则重复的问题。



最后检查时间：2021-02-04 02:53:45。

## 规则统计

总计规则：1137 条。

各类型规则统计：

| 类型 | 数量(条) |
| ---- | ---- |
| USER-AGENT | 57 |
| DOMAIN-SUFFIX | 182 |
| DOMAIN-KEYWORD | 20 |
| DOMAIN | 31 |
| IP-CIDR | 847 |
## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### Shadowrocket 
实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia.list

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Shadowrocket/GlobalMedia/GlobalMedia.list

## 重复统计


当前分流规则，未包含其他子规则。


当前分流规则，与本项目其他分流规则重复情况统计(点击重复数量可查看明细)。



| 名称 | 数量 | 重复 | 重合度 |
| ---- | ---- | ---- | ------ |
|  [China](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/China)    | 689   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   0.29% |
|  [ChinaTest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/ChinaTest)    | 71479   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   0.0% |
|  [Apple](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Apple)    | 105   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   3.81% |
|  [AppleNews](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/AppleNews)    | 11   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   81.82% |
|  [AppleTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/AppleTV)    | 7   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   42.86% |
|  [YouTube](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/YouTube)    | 182   | [11](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   6.04% |
|  [Google](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Google)    | 104   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   2.88% |
|  [YouTubeMusic](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/YouTubeMusic)    | 4   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   100.0% |
|  [AdvertisingLite](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/AdvertisingLite)    | 22826   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   0.01% |
|  [Advertising](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Advertising)    | 50420   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   0.01% |
|  [AdvertisingTest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/AdvertisingTest)    | 73864   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   0.01% |
|  [Proxy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Proxy)    | 28251   | [199](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   0.7% |
|  [Global](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Global)    | 1293   | [165](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   12.76% |
|  [BlackList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/BlackList)    | 772   | [18](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   2.33% |
|  [Speedtest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Speedtest)    | 5   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   20.0% |
|  [Netflix](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Netflix)    | 42   | [42](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   100.0% |
|  [TikTok](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/TikTok)    | 16   | [11](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   68.75% |
|  [Disney](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Disney)    | 132   | [18](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   13.64% |
|  [Spotify](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Spotify)    | 19   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   52.63% |
|  [Spark](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Spark)    | 5   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   20.0% |
|  [Niconico](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Niconico)    | 10   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   50.0% |
|  [BBC](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/BBC)    | 17   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   47.06% |
|  [Amazon](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Amazon)    | 26   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   34.62% |
|  [Bahamut](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Bahamut)    | 5   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   60.0% |
|  [Adobe](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Adobe)    | 34   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   2.94% |
|  [AbemaTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/AbemaTV)    | 22   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   22.73% |
|  [All4](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/All4)    | 3   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   100.0% |
|  [AmazonPrimeVideo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/AmazonPrimeVideo)    | 26   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   34.62% |
|  [DAZN](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/DAZN)    | 19   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   47.37% |
|  [Deezer](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Deezer)    | 3   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   100.0% |
|  [EncoreTVB](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/EncoreTVB)    | 6   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   66.67% |
|  [Fox](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Fox)    | 257   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   3.11% |
|  [HBO](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/HBO)    | 31   | [12](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   38.71% |
|  [HWTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/HWTV)    | 3   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   100.0% |
|  [Hulu](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Hulu)    | 55   | [11](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   20.0% |
|  [ITV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/ITV)    | 4   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   100.0% |
|  [JOOX](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/JOOX)    | 4   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   100.0% |
|  [Japonx](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Japonx)    | 10   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   100.0% |
|  [KKBOX](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/KKBOX)    | 7   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   71.43% |
|  [LiTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/LiTV)    | 2   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   50.0% |
|  [LineTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/LineTV)    | 8   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   25.0% |
|  [My5](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/My5)    | 4   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   75.0% |
|  [PBS](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/PBS)    | 2   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   100.0% |
|  [Pandora](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Pandora)    | 3   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   100.0% |
|  [Qobuz](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Qobuz)    | 33   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   3.03% |
|  [SoundCloud](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/SoundCloud)    | 4   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   100.0% |
|  [TIDAL](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/TIDAL)    | 4   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   75.0% |
|  [TVB](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/TVB)    | 15   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   20.0% |
|  [TaiWanGood](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/TaiWanGood)    | 3   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   66.67% |
|  [ViuTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/ViuTV)    | 10   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/GlobalMedia/GlobalMedia_Repeat.list)   |   40.0% |
### 特别说明
程序在实际运算时，会根据DOMAIN、DOMAIN-SUFFIX、IP-CIDR、IP-CIDR6间的包含关系进行去重，而出于运行效率考虑，重复规则只统计纯文本匹配，所以可能与实际效果有所出入，仅供参考。

## 数据来源

本项目的GlobalMedia分流规则的数据来自以下链接，通常已涵盖所有数据来源的分流规则。如果你正在使用这些分流规则，建议不要与本项目的GlobalMedia分流规则混合使用，以免造成规则重复。

- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ProxyMedia.list
- https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/Ruleset/GlobalMedia.list
- https://raw.githubusercontent.com/GeQ1an/Rules/master/QuantumultX/Filter/GMedia.list
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/connershua/Quantumult/X/Filter/ForeignMedia.list
- https://raw.githubusercontent.com/eHpo1/Rules/master/Surge4/Ruleset/GlobalMedia.list
- https://raw.githubusercontent.com/sve1r/Rules-For-Quantumult-X/develop/Rules/Media/ForeignMedia.list
- https://raw.githubusercontent.com/sve1r/Rules-For-Quantumult-X/develop/Rules/Media/ForeignMedia_New.list


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

欢迎通过[issues](https://github.com/blackmatrix7/ios_rule_script/issues/new)提交反馈，共同完善本项目的GlobalMedia分流规则。

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