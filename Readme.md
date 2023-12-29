## [Update on 2023-12-19](https://github.com/Mxucc/QuantumultX/blob/master/README.md)

* 本仓库以[Orz-3/QuantumultX](https://github.com/Orz-3/QuantumultX)的配置为主,具体看Mxu.conf文件具体内容（以下Readme可能有误，以实际为准）

## 使用方法：

*  1.点击库中的Orz-3.conf文件，点击raw获取真实地址，复制地址备用(手机端是点代码右上方的三个点，然后点View
* 2.Quan X主界面，点击右下角风车，然后弹出界面下拉至 配置文件-下载，点击下载，将上一步复制的地址粘贴到弹出窗口，然后点确定
* 3.Quan X主界面，点击右下角风车，然后弹出界面下拉至 Mitm ，点击生成证书
* 4.然后回到Quan X，继续点击配置证书，根据提示安装证书
* 5.安装成功后启用证书，并到系统的 设置-通用-关于本机 点击信任证书
* 6.打开重写和Mitm
* 7.添加节点/订阅，具体为在Quan X主界面点击右下角风车-节点-引用(订阅)，然后点右上角添加，填写标签和资源路径（重要，不添加标签是无法筛选的)
* 8.开始使用

## 1️⃣QuantumultX 小白2.0配置
* 配置更新时间：2023-12-06[QuantumultX小白配置](https://github.com/Orz-3/QuantumultX) 2023-12-15[QuantumultX ddgksf2013配置](https://github.com/ddgksf2013/ddgksf2013)
* Mxu自用QX配置 [***conf***](https://raw.githubusercontent.com/Mxucc/QuantumultX/main/Mxu.conf) 
* 上述配置支持QX商店最新版，包括图标库订阅、超级VIP、网易云音乐解锁教程、旧版应用推荐、IOS更新屏蔽、智能分流、墨鱼去开屏2.0、各种APP净化、Boxjs订阅、流媒体解锁查询、高德地图知乎去广告...
* 可借助 ghproxy 为 GitHub 加速：在 ```https://raw.githubusercontent.com/``` 前添加 ```https://ghproxy.com/```
> 详细的带图指南请参考 [*@Shawn*](https://t.me/QuanX_API) 提供的 [***Quantumult X 不完全指南***](https://www.notion.so/Quantumult-X-1d32ddc6e61c4892ad2ec5ea47f00917#bb2dce7c01114955bbdbbd222f2a5fcf)

## 2️⃣QuantumultX 分流：
* 网易云音乐分流 [*NeteaseMusic.list*](https://github.com/ddgksf2013/Filter/raw/master/NeteaseMusic.list)
* 自用 ChatGPT 分流 [*OpenAi.list*](https://raw.githubusercontent.com/ddgksf2013/Filter/master/OpenAi.list)
* IP隐藏の分流[不建议使用] [*Anti-ip.list*](https://github.com/ddgksf2013/Filter/raw/master/anti-ip-attribution.list)
* Emby分流 [*Emby.list*](https://github.com/ddgksf2013/Filter/blob/master/Emby.list)
> 更多的分流请参考 [*@blackmatrix7*](https://github.com/blackmatrix7) 提供的 [***Quantumult X 分流***](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX)

## 3️⃣QuantumultX 复写：
<table>
    <tr> <th> 类别 </th> <th> 序号 </th> <th> 功能 </th> <th> 链接 </th> <th> 作者 </th> </tr >
    <tr>
		<td rowspan="8"><strong>会员解锁</strong></td>
		<td > 1</td> <td > 真B站去广告+解锁普通视频<br><strong><em>1080P高码率</em></strong> </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/Bilibili.conf"><em>BilibiliVip.conf</em></a></td><td>ddgksf2013</td>
    </tr>	
	<tr>
		<td > 2 </td> <td > Spotify会员 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/UnlockVip/Spotify.conf"><em>SpotifyPro.conf</em></a></td><td>app2smile</td>
    </tr>
	<tr>
		<td > 3</td> <td > 墨鱼专属VIP </td> <td ><a href="https://github.com/ddgksf2013/dev/raw/master/ForOwnUse.conf"><em>ForOwnUse.conf</em></a></td><td>ddgksf2013</td>
    </tr>
	<tr>
		<td > 4 </td> <td ><s>  酷我纯净版SVIP+</s> 净化 </td> <td ><a href="https://gist.githubusercontent.com/ddgksf2013/0f76e952f0c4a2579932f45a209b40c3/raw/Kuwo.conf"><em>Kuwo.conf</em></a></td><td>ddgksf2013</td>
    </tr>
	<tr>
		<td > 5 </td> <td > 财新周刊VIP </td> <td ><a href="https://github.com/ddgksf2013/MoYu/raw/master/CaiXinZhouKanProCrack.js"><em>CXZK.vip.js</em></a></td><td>ddgksf2013</td>
    </tr>
	<tr>
		<td > 6 </td> <td > Nicegram高级版 </td> <td ><a href="https://raw.githubusercontent.com/ddgksf2013/MoYu/master/NicegramProCrack.js"><em>Nicegram.pro.js</em></a></td><td>ddgksf2013</td>
    </tr>
	<tr>
		<td > 7 </td> <td > RevenueCat多合一 </td> <td ><a href="https://gist.githubusercontent.com/ddgksf2013/dbb1695cd96743eef18f3fac5c6fe227/raw/revenuecat.js"><em>revenuecat.js</em></a></td><td>ddgksf2013</td>
    </tr>
	<tr>
		<td > 8 </td> <td > BuyiTunes多合一 </td> <td ><a href="https://gist.githubusercontent.com/ddgksf2013/9e0f6c7341beea09a31aa309d9d7f502/raw/buyitunes.js"><em>buyitunes.js</em></a></td><td>ddgksf2013</td>
    </tr>
	<tr>
		<td colspan="5">  </td>
    </tr>
    <tr>
		<td rowspan="26"><strong>广告屏蔽</strong></td>
		<td > 1 </td> <td > 微信小程序去广告 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/Applet.conf"><em>Applet.conf</em></a></td><td>ddgksf2013</td>
    </tr>
    <tr>
		<td > 2 </td> <td > 墨鱼去开屏2.0 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/StartUp.conf"><em>StartUp.conf</em></a></td><td>ddgksf2013</td>
    </tr>
    <tr>
		<td > 3 </td> <td > 油管广告屏蔽<br><strong><em>视频自动PIP+背景播放</strong></em> </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/YoutubeAds.conf"><em>YoutubeAds.conf</em></a></td><td>divineEngine<br>Maasea</td>  
    </tr>
	<tr>
		<td > 4 </td> <td > 公众号图文去广告<br><strong><em>无法去除朋友圈AD</strong></em> </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/WeChat.conf"><em>WeChatAdBlock.conf</em></a></td><td>ddgksf2013</td>
    </tr>
	<tr>
		<td > 5 </td> <td > 知乎去广告 </td> <td ><a href="https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/zheye/zheye.snippet"><em>Zhihu_Plus.conf</em></a></td><td>blackmatrix7</td>  
    </tr>
	<tr>
		<td > 6 </td> <td > 百度贴吧去广告 </td> <td ><a href="https://github.com/app2smile/rules/raw/master/module/tieba-qx.conf"><em>Tieba_Ads.conf</em></a></td><td>app2smile</td>  
    </tr>
	<tr>
		<td > 7 </td> <td > 百度网盘去广告 </td> <td ><a href="https://gist.githubusercontent.com/ddgksf2013/f43026707830c7818ee3ba624e383c8d/raw/baiduCloud.vip.js"><em>BdPanAdBlock.conf</em></a></td><td>ddgksf2013</td>  
    </tr>
		<tr>
		<td > 8 </td> <td > <strong><em>喜马拉雅去广告</strong></em> </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/Ximalaya.conf"><em>XmlyAdBlock.conf</em></a></td><td>ddgksf2013</td>  
    </tr>
	<tr>
		<td > 9 </td> <td > 小红书去水印</td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/XiaoHongShu.conf"><em>XiaoHongShu.conf</em></a></td><td>ddgksf2013</td>  
    </tr>
	<tr>
		<td > 10 </td> <td > Keep超级净化</td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/KeepStyle.conf"><em>keepStyle.conf</em></a></td><td>ddgksf2013</td>  
    </tr>
	<tr>
		<td > 11 </td> <td > <strong>Pixiv去广告 </strong></td> <td ><a href="https://github.com/ddgksf2013/Scripts/raw/master/pixivAds.js"><em>PixivAds.js</em></a></td><td>ddgksf2013</td>  
    </tr>
	<tr>
		<td > 12 </td> <td > 酷安去广告</td> <td ><a href="https://github.com/ddgksf2013/Scripts/raw/master/coolapk.js"><em>coolapk.js</em></a></td><td>ddgksf2013</td>  
    </tr>
	<tr>
		<td > 13 </td> <td > 12306去广告</td> <td ><a href="https://github.com/ddgksf2013/Scripts/raw/master/12306.js"><em>12306.js</em></a></td><td>ddgksf2013</td>  
    </tr>
	<tr>
		<td > 14 </td> <td >[未适配新版] <s> 多多视频去广告</s>  </td> <td ><s> <a href="https://raw.githubusercontent.com/ddgksf2013/Scripts/master/rrtv_json.js"><em>DuoduoVideoAds.js</em></a></s> </td><td>ddgksf2013</td>  
    </tr>
	<tr>
		<td > 15 </td> <td > <strong>微博(国际版)去广告 </strong></td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/Weibo.conf"><em>Weibo.conf</em></a></td><td>ddgksf2013</td>  
    </tr>
	<tr>
		<td > 16 </td> <td > 高德地图去广告[卸载重装] </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/Amap.conf"><em>Amap.conf</em></a></td><td>ddgksf2013</td>  
    </tr>
	<tr>
		<td > 17 </td> <td > 网易云去广告 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/Netease.conf"><em>Netease.conf</em></a></td><td>ddgksf2013</td>  
    </tr>
	<tr>
		<td > 18 </td> <td > 菜鸟裹裹去广告 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/Cainiao.conf"><em>Cainiao.conf</em></a></td><td>ddgksf2013</td>  
    </tr>
	<tr>
		<td > 19 </td> <td > 起点去广告[卸载重装] </td> <td ><a href="https://raw.githubusercontent.com/app2smile/rules/master/module/qidian.conf"><em>qidian.conf</em></a></td><td>app2smile</td>  
    </tr>
	<tr>
		<td > 20 </td> <td > 随手记去广告 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/SuiShouJi.conf"><em>SuiShouJi.conf</em></a></td><td>ddgksf2013</td>  
    </tr>
	<tr>
		<td > 21 </td> <td > Bing首页简化 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/BingSimplify.conf"><em>BingSimplify.conf</em></a></td><td>ddgksf2013</td>  
    </tr>
	<tr>
		<td > 22 </td> <td >[新版失效]<s> 优酷净化[卸载重装]</s> </td> <td ><s> <a href="https://gist.githubusercontent.com/ddgksf2013/5b431857f8b88acbc7ac2453a21e676a/raw/youku.adblock.js"><em>youku.adblock.js</em></a></s> </td><td>ddgksf2013</td>  
    </tr>
    <tr>
		<td > 23 </td> <td > 百度地图净化[卸载重装] </td> <td ><a href="https://gist.githubusercontent.com/ddgksf2013/beec132ca0c3570ffa0cf331bce8f82a/raw/baidumap.adblock.conf"><em>baidumap.conf</em></a></td><td>ddgksf2013</td>  
    </tr>
<tr>
		<td > 24 </td> <td > 皮皮虾净化及去水印 </td> <td ><a href="https://gist.githubusercontent.com/ddgksf2013/bb1dadbd32f67c68772caebcc70b0a33/raw/pipixia.adblock.js"><em>pipixia.adblock.js</em></a></td><td>Liquor030</td>  
    </tr>
	<tr>
		<td > 25 </td> <td > 什么值得买 </td> <td ><a href="https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/smzdm/smzdm_remove_ads.qxrewrite"><em>smzdmAds.conf</em></a></td><td>blackmatrix7</td>  
    </tr>
			<tr>
		<td > 26 </td> <td > 微信阅读精简 </td> <td ><a href="https://raw.githubusercontent.com/Maasea/sgmodule/master/WeRead.sgmodule"><em>WeRead.sgmodule</em></a></td><td>Maasea</td>  
    </tr>
	<tr>
		<td colspan="5">  </td>
    </tr>
	<tr>
		<td rowspan="12"><strong>应用增强</strong></td>
		<td > 1 </td> <td > <s>B站自动换区</s>[不适用新版] </td> <td ><s><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Function/BilibiliAutoRegion.conf"><em>BilibiliAutoRegion.conf</em></a></s></td><td>Nobyda</td>
    </tr>
	<tr>
		<td > 2 </td> <td > <strong>B站CC繁体字幕转简体</strong> </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Function/Bilibili_CC.conf"><em>Bilibili_CC.conf</em></a></td><td>ddgksf2013</td>
    </tr>
	<tr>
		<td > 3 </td> <td > 百度网盘净化+解锁倍速 </td> <td ><a href="https://gist.githubusercontent.com/ddgksf2013/f43026707830c7818ee3ba624e383c8d/raw/baiduCloud.vip.js"><em>BaiduCloud.conf</em></a></td><td>ddgksf2013</td>
    </tr>
	<tr>
		<td > 4 </td> <td > Youtube无中文字幕机翻方案 </td> <td ><a href="https://raw.githubusercontent.com/id77/QuantumultX/master/rewrite/Youtube_CC.conf#out=Hant"><em>Youtube_CC.conf</em></a></td><td>id77</td>
    </tr>
	<tr>
		<td > 5 </td> <td > 各种流媒体字幕翻译 </td> <td ><a href="https://raw.githubusercontent.com/Neurogram-R/Quantumult-X/main/snippet/Dualsub.snippet"><em>Dualsub.conf</em></a></td><td>Neurogram-R</td>
    </tr>
	<tr>
		<td > 6 </td> <td > 微信110解锁被屏蔽的URL </td> <td ><a href="https://github.com/zZPiglet/Task/raw/master/UnblockURLinWeChat.conf"><em>WeChat110.conf</em></a></td><td>zZPiglet</td>
    </tr>
	<tr>
		<td > 7 </td> <td > 指南针解锁经纬度 </td> <td ><a href="https://raw.githubusercontent.com/VirgilClyne/iRingo/main/snippet/Location.snippet"><em>Location.conf</em></a></td><td>VirgilClyne</td>
    </tr>
	<tr>
		<td > 8 </td> <td > Testflight共享+解锁区域限制 </td> <td ><a href="https://raw.githubusercontent.com/NobyDa/Script/master/TestFlight/TestFlightAccount.js"><em>TestFlightAccount.conf</em></a></td><td>NobyDa</td>
    </tr>
	<tr>
		<td > 9 </td> <td > UposRedirect </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Function/UposRedirect.conf"><em>UposRedirect.conf</em></a></td><td>ddgksf2013</td>
    </tr>
	<tr>
		<td > 10 </td> <td > <strong>阿里云盘倍速</strong> </td> <td ><a href="https://gist.githubusercontent.com/ddgksf2013/f4752e632fd3375ea2811985c5b635dc/raw/alicloud.js"><em>alicloud.js</em></a></td><td>ddgksf2013</td>
    </tr>
	<tr>
		<td > 11 </td> <td > Spotify歌词翻译 </td> <td ><a href="https://raw.githubusercontent.com/app2smile/rules/master/js/spotify-lyric.js"><em>spotify-lyric.js</em></a></td><td>app2smile</td>
    </tr>
			<tr>
		<td > 12 </td> <td > VVebo修复用户时间线 </td> <td ><a href="https://raw.githubusercontent.com/bin64/Scripts/main/QuantumultX/vvebo.js"><em>vvebo.js</em></a></td><td>suiyuran</td>  
    </tr>
	<tr>
		<td colspan="5">  </td>
    </tr>
	<tr>
		<td rowspan="6"><strong>网页优化</strong></td>
		<td > 1 </td> <td > 自用影视网站去广告 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Html/WebAdBlock.conf"><em>WebAdBlock.conf</em></a></td><td>ddgksf2013</td>
    </tr>
	<tr>
		<td > 2 </td> <td > Google自动翻页 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Html/EndlessGoogle.conf"><em>EndlessGoogle.conf</em></a></td><td>langkhach</td>
    </tr>
	<tr>
		<td > 3 </td> <td > <strong><em>Safari超级搜索V2.0</em></strong><br>翻译·社区·购物·换区·视频·引擎  </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Html/Q-Search.conf"><em>Q-Search.conf</em></a></td><td>ddgksf2013</td>
    </tr>
	<tr>
		<td > 4 </td> <td > 豆瓣电影<br><strong><em>网页优化+快捷观影</em></strong>  </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Html/Douban.conf"><em>Douban.conf</em></a></td><td>ddgksf2013</td>
    </tr>
	<tr>
		<td > 5 </td> <td > 解锁NewBing搜索 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Html/NewBing.conf"><em>NewBing.conf</em></a></td><td>Nobyda<br>ddgksf2013</td>
    </tr>
	<tr>
		<td > 6 </td> <td > 百度搜索去广告 </td> <td ><a href="https://raw.githubusercontent.com/limbopro/Adblock4limbo/main/Adblock4limbo.conf"><em>Adblock4limbo.conf</em></a></td><td>limbopro</td>
    </tr>
</table>

> 更多的重写请参考 [*@ddgksf2013*](https://github.com/ddgksf2013) 提供的 [***Quantumult X 重写配置***](https://github.com/ddgksf2013/Rewrite/tree/master)

## 4️⃣QuantumultX 脚本Task：
- [x] QX每日色图脚本 [*setu.js*](https://github.com/ddgksf2013/Scripts/raw/master/setu.js)
- [x] 得宝小程序签到 [*db.js*](https://github.com/ddgksf2013/Scripts/raw/master/debao.js)
- [x] 同程旅行小程序签到 [*tclx.js*](https://github.com/ddgksf2013/Scripts/raw/master/tclx.js)
- [x] 书香门第网页签到 [*sxmd.js*](https://github.com/ddgksf2013/Scripts/raw/master/shuxiangmendi.js)
- [x] 每天60s读懂世界 [*60s.js*](https://github.com/ddgksf2013/Scripts/raw/master/60s.js)
- [x] Glados签到 [*glados.js*](https://gist.githubusercontent.com/ddgksf2013/32b3d37d78433a34370cbfb69780160d/raw/glados.js)
- [x] Emby自动保号 [*emby.js*](https://gist.githubusercontent.com/ddgksf2013/e6793129fba99bb539cd7a49f74a48fa/raw/embyAutoSign.js)
> 更多的签到脚本请参考 [*@Chavyleung*](https://github.com/chavyleung) 提供的 [***Quantumult X 签到脚本***](https://github.com/chavyleung/scripts/blob/master/QuantumultX_Remote_Task.conf)

## 5️⃣QuantumultX 图标库


| 序号 | 点击名称快捷添加图标订阅 | 作者 |
| :----: | :---- | :----: |
| 1  | [Qure图标库（彩色1）](https://quantumult.app/x/open-app/ui?module=gallery&type=icon&action=add&content=%5B%0A%20%20%20%20%22https%3A%2F%2Fgithub.com%2FKoolson%2FQure%2Fraw%2Fmaster%2FOther%2FQureColor-All.json%22%0A%5D) | Koolson |
| 2  | [Qure图标库（彩色2）](https://quantumult.app/x/open-app/ui?module=gallery&type=icon&action=add&content=%5B%0A%20%20%20%20%22https%3A%2F%2Fraw.githubusercontent.com%2FKoolson%2FQure%2Fmaster%2FOther%2FQureColor.json%22%0A%5D) | Koolson | 
| 3  | [Qure图标库（mini）](https://quantumult.app/x/open-app/ui?module=gallery&type=icon&action=add&content=%5B%0A%20%20%20%20%22https%3A%2F%2Fraw.githubusercontent.com%2FKoolson%2FQure%2Fmaster%2FOther%2FQuremini.json%22%0A%5D) |  Koolson |
| 4  | [Orz-3图标库（mini style）](https://quantumult.app/x/open-app/ui?module=gallery&type=icon&action=add&content=%5B%0A%20%20%20%20%22https%3A%2F%2Fgithub.com%2FOrz-3%2Fmini%2Fraw%2Fmaster%2Fmini.json%22%0A%5D) | Orz-3 |
| 5  | [Orz-3图标库（mini color）](https://quantumult.app/x/open-app/ui?module=gallery&type=icon&action=add&content=%5B%0A%20%20%20%20%22https%3A%2F%2Fraw.githubusercontent.com%2FOrz-3%2Fmini%2Fmaster%2FminiColor.json%22%0A%5D) | Orz-3 |
| 6  | [泡泡图标库 ](https://quantumult.app/x/open-app/ui?module=gallery&type=icon&action=add&content=%5B%0A%20%20%20%20%22https%3A%2F%2Fraw.githubusercontent.com%2Ftugepaopao%2FImage-Storage%2Fmaster%2Fother%2FCute.json%22%0A%5D) | tugepaopao |
| 7 | [小猫咪库](https://quantumult.app/x/open-app/ui?module=gallery&type=icon&action=add&content=%5B%0A%20%20%20%20%22https%3A%2F%2Fraw.githubusercontent.com%2FYuanxsxs%2FQtumultX%2Fmaster%2FIcon%2FCatcat.json%22%0A%5D) | Yuanxsxs |
| 8 | [姿势图标库](https://quantumult.app/x/open-app/ui?module=gallery&type=icon&action=add&content=%5B%0A%20%20%20%20%22https%3A%2F%2Fraw.githubusercontent.com%2FLovedGM%2FQuantumult-X-TuBiao%2Fmain%2Fzishi-cs.json%22%0A%5D) | LovedGM | 
| 9 | [Semporia库 ](https://quantumult.app/x/open-app/ui?module=gallery&type=icon&action=add&content=%5B%0A%20%20%20%20%22https%3A%2F%2Fraw.githubusercontent.com%2FSemporia%2FHand-Painted-icon%2Fmaster%2FSemporia.json%22%0A%5D) | Semporia |

> 更多的图标订阅请参考 [*@ddgksf2013*](https://github.com/ddgksf2013) 集合的 [***Quantumult X 图标库***](https://github.com/ddgksf2013/Icon/blob/master/README.md)

## 6️⃣Awesome Resource：
* QuantumultX测试版[***更新日志***](https://github.com/ddgksf2013/Profile/raw/master/QX_TestFlight_Update.log)
* 屏蔽IOS更新[***点我***](https://initnil.com/tvOS.mobileconfig)
* 自用Clash配置 [*ClashforWindows.yaml*](https://raw.githubusercontent.com/ddgksf2013/Profile/master/ClashforWindows.yaml)
* 1080P超清IPTV国内[***直播源***](https://github.com/ddgksf2013/M3U8LIST/raw/master/IPTV2022.m3u)
* Clash详细教程 [*Documents.md*](https://docs.cfw.lbyczf.com/contents/quickstart.html)
* 自用 ACA Emby 机场 [***htts://www.aca.best***](https://www.acaisbest.com/#/register?code=t1qwfcOL)
* 墨鱼网盘资源 [*Tg.md*](https://t.me/ddgksf2023): TrollStore、Windows、Cracker.ipa、Android.apk...
* [***自用优秀Web网站合集***](https://github.com/ddgksf2013/WebSite)：影视、工具、下载、阅读、Porn...
* IOS手机端应用推荐[*Appraven.net*](https://appraven.net/collection/37743082)
* 自用小火箭最简配置[*Shadowrocket.conf*](https://github.com/ddgksf2013/Profile/raw/master/Shadowrocket.conf)
* 微信屏蔽朋友圈广告[*WeChat.web*](https://mp.weixin.qq.com/s/f_miMTmLOTDnk4C0OanHyw)
* IOS、Android[TV]、Web、AppleTV观影方案[***Notion.md***](https://ddgksf2013.notion.site/IOS-Android-TV-Web-AppleTV-737275e3de2c4def86196d8c982ef86e?pvs=4)
* 如何有效减少Android、IOS端应用开屏广告的打扰？[*WeChat.web*](https://mp.weixin.qq.com/s/DOwEQs4Z7eFpGWOVAO-2QA)


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 8️⃣特别感谢：

[*@ddgksf2013*](https://t.me/ddgksf2013_bot)
[*@Orz-3*](https://github.com/Orz-3) 

### [回到顶部](https://github.com/ddgksf2013/ddgksf2013)