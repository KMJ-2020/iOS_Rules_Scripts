# Global

## 前言

本项目的Global分流规则由爬虫程序自动维护。

定时爬取互联网上开源的Global分流规则，将其进行清洗、去重、合并、优化后，形成单一的分流规则文件，旨在解决引用大量外部规则造成规则重复的问题。


Global分流规则中含有URL-REGEX类型，此类的规则对于HTTPS请求需要MITM使用才能生效。程序已默认根据正则推导一份MITM的模块/复写/插件在当前分流规则的目录中，便于参考搭配使用。

最后检查时间：2021-02-04 02:53:13。

## 规则统计

总计规则：1293 条。

各类型规则统计：

| 类型 | 数量(条) |
| ---- | ---- |
| DOMAIN-SUFFIX | 1127 |
| DOMAIN-KEYWORD | 27 |
| IP-CIDR | 66 |
| IP-CIDR6 | 3 |
| USER-AGENT | 39 |
| DOMAIN | 29 |
| PROCESS-NAME | 1 |
| URL-REGEX | 1 |
## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### Surge 
实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global.list

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Domain.list

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Surge/Global/Global.list

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Surge/Global/Global_Domain.list

如果稳定版无法访问 ，可能是尚未从实时版的分支合并，建议您先使用实时版，或等待下次稳定版分支合并。

### 特别说明

Global.list请使用RULE-SET。

Global_Domain.list请使用DOMAIN-SET。

## 重复统计


当前分流规则，未包含其他子规则。


当前分流规则，与本项目其他分流规则重复情况统计(点击重复数量可查看明细)。



| 名称 | 数量 | 重复 | 重合度 |
| ---- | ---- | ---- | ------ |
|  [China](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/China)    | 689   | [36](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   5.22% |
|  [ChinaTest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/ChinaTest)    | 71479   | [39](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   0.05% |
|  [Apple](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Apple)    | 105   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   2.86% |
|  [AppStore](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AppStore)    | 2   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [TestFlight](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/TestFlight)    | 3   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   33.33% |
|  [AppleBlock](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AppleBlock)    | 6   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [AppleTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AppleTV)    | 7   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   14.29% |
|  [Github](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Github)    | 6   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   66.67% |
|  [OneDrive](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/OneDrive)    | 19   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   21.05% |
|  [Microsoft](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Microsoft)    | 101   | [21](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   20.79% |
|  [YouTube](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/YouTube)    | 182   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   5.49% |
|  [Google](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Google)    | 104   | [59](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   56.73% |
|  [YouTubeMusic](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/YouTubeMusic)    | 4   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   50.0% |
|  [AdvertisingLite](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AdvertisingLite)    | 22826   | [11](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   0.05% |
|  [Advertising](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Advertising)    | 50420   | [29](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   0.06% |
|  [AdvertisingTest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AdvertisingTest)    | 73864   | [33](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   0.04% |
|  [Game](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Game)    | 64   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   14.06% |
|  [Steam](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Steam)    | 32   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   3.12% |
|  [PlayStation](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/PlayStation)    | 4   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Epic](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Epic)    | 15   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   6.67% |
|  [Gog](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Gog)    | 3   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   33.33% |
|  [Nintendo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Nintendo)    | 123   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   3.25% |
|  [Xbox](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Xbox)    | 34   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   2.94% |
|  [Proxy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Proxy)    | 28251   | [1256](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   4.45% |
|  [GlobalMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/GlobalMedia)    | 1137   | [165](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   14.51% |
|  [BlackList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/BlackList)    | 772   | [677](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   87.69% |
|  [Speedtest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Speedtest)    | 5   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   20.0% |
|  [Telegram](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Telegram)    | 19   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   52.63% |
|  [KakaoTalk](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/KakaoTalk)    | 10   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   40.0% |
|  [Line](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Line)    | 22   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   31.82% |
|  [Netflix](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Netflix)    | 42   | [28](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   66.67% |
|  [Dubox](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Dubox)    | 2   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Disney](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Disney)    | 132   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   6.06% |
|  [Twitter](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Twitter)    | 11   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   90.91% |
|  [Cloudflare](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Cloudflare)    | 22   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   4.55% |
|  [Facebook](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Facebook)    | 39   | [39](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Spotify](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Spotify)    | 19   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   36.84% |
|  [Wikipedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Wikipedia)    | 12   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   41.67% |
|  [Discord](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Discord)    | 6   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   50.0% |
|  [PayPal](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/PayPal)    | 5   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   60.0% |
|  [Spark](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Spark)    | 5   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   80.0% |
|  [Sony](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Sony)    | 6   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   83.33% |
|  [Niconico](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Niconico)    | 10   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   50.0% |
|  [BBC](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/BBC)    | 17   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   35.29% |
|  [Developer](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Developer)    | 23   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   26.09% |
|  [Amazon](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Amazon)    | 26   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   34.62% |
|  [Instagram](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Instagram)    | 2   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Scholar](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Scholar)    | 76   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   1.32% |
|  [Whatsapp](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Whatsapp)    | 21   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   19.05% |
|  [Bahamut](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Bahamut)    | 5   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   60.0% |
|  [Adobe](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Adobe)    | 34   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   26.47% |
|  [AbemaTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AbemaTV)    | 22   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   22.73% |
|  [All4](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/All4)    | 3   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [AmazonPrimeVideo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AmazonPrimeVideo)    | 26   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   30.77% |
|  [AppleDaily](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AppleDaily)    | 13   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   15.38% |
|  [BoXun](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/BoXun)    | 2   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   50.0% |
|  [CNN](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/CNN)    | 6   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   16.67% |
|  [CableTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/CableTV)    | 2   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   50.0% |
|  [DAZN](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/DAZN)    | 19   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   21.05% |
|  [Dailymotion](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Dailymotion)    | 4   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   25.0% |
|  [Deezer](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Deezer)    | 3   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [EncoreTVB](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/EncoreTVB)    | 6   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   50.0% |
|  [Fox](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Fox)    | 257   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   2.72% |
|  [HBO](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/HBO)    | 31   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   22.58% |
|  [HWTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/HWTV)    | 3   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Huffpost](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Huffpost)    | 18   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   5.56% |
|  [Hulu](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Hulu)    | 55   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   9.09% |
|  [ITV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/ITV)    | 4   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   75.0% |
|  [JOOX](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/JOOX)    | 4   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   75.0% |
|  [KKBOX](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/KKBOX)    | 7   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   71.43% |
|  [Kakao](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Kakao)    | 14   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   42.86% |
|  [LiTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/LiTV)    | 2   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   50.0% |
|  [LineTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/LineTV)    | 8   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   50.0% |
|  [My5](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/My5)    | 4   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   75.0% |
|  [NYTimes](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/NYTimes)    | 16   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   50.0% |
|  [Nikkei](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Nikkei)    | 3   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   33.33% |
|  [PBS](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/PBS)    | 2   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [Pandora](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Pandora)    | 3   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [SoundCloud](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/SoundCloud)    | 4   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [TIDAL](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/TIDAL)    | 4   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   25.0% |
|  [TVB](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/TVB)    | 15   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   20.0% |
|  [TaiWanGood](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/TaiWanGood)    | 3   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   100.0% |
|  [VOA](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/VOA)    | 51   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   3.92% |
|  [Vimeo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Vimeo)    | 16   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   18.75% |
|  [ViuTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/ViuTV)    | 10   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   40.0% |
|  [Voxmedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Voxmedia)    | 16   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   12.5% |
|  [friDay](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/friDay)    | 2   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Global/Global_Repeat.list)   |   50.0% |
### 特别说明
程序在实际运算时，会根据DOMAIN、DOMAIN-SUFFIX、IP-CIDR、IP-CIDR6间的包含关系进行去重，而出于运行效率考虑，重复规则只统计纯文本匹配，所以可能与实际效果有所出入，仅供参考。

## 数据来源

本项目的Global分流规则的数据来自以下链接，通常已涵盖所有数据来源的分流规则。如果你正在使用这些分流规则，建议不要与本项目的Global分流规则混合使用，以免造成规则重复。

- https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/Ruleset/Global.list
- https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/Ruleset/GlobalMedia.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Global.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Global.list
- https://raw.githubusercontent.com/eHpo1/Rules/master/Surge4/Ruleset/Global.list
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