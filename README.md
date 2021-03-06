# flutter_plugins

集合常用Flutter插件以做记录方面借鉴

## 三方SDK部分(推送、地图、IM等常用三方SDK)

### 推送部分



| 库名  | 链接  | 简介  |
|:----------|:----------|:----------|
| mobpush_plugin ![](https://img.shields.io/pub/v/mobpush_plugin.svg)  | [官网](https://www.mob.com/wiki/detailed/?wiki=MobPushForFlutterfenlei&id=136) [Pub](https://pub.dev/packages/mobpush_plugin) [GitHub](https://github.com/MobClub/MobPush-for-Flutter)   |MobTech官方开发维护: Android支持厂商通道, 推送到达率还可以,可能由于免费原因共享推送带宽延时稍微有点高；***关键免费*** 而且该公司其它产品大多都是支持Flutter的- <font color=red>***提供5种非Native平台插件***</font>|
|jpush_flutter ![](https://img.shields.io/pub/v/jpush_flutter.svg)|[官网](http://docs.jiguang.cn/jpush/client/client_plugins/) [Pub](https://pub.flutter-io.cn/packages/jpush_flutter) [GitHub](https://github.com/jpush/jpush-flutter-plugin)|极光官方维护:Android 支持厂商通道 到达率很高，厂商通道需要联系商务，顾名思义就是要钱-<font color=red>***提供8种非Native平台插件***</font>|
| getuiflut ![](https://img.shields.io/pub/v/getuiflut.svg)|[官网](http://docs.getui.com/getui/more/plugin/) [Pub](https://pub.flutter-io.cn/packages/getuiflut) [GitHub](https://github.com/GetuiLaboratory/getui-flutter-plugin)| 个推官方开发维护-<font color=red>***提供8种非Native平台插件***</font>
| tpns_flutter_plugin |[官网](https://cloud.tencent.com/document/product/548/41515) [腾讯工蜂](https://git.code.tencent.com/tpns/XG-Flutter-Plugin)|腾讯信鸽(tpns)官方开发维护-<font color=red>***提供3种非Native平台插件***</font>


### 地图部分

| 库名  | 链接  | 简介  |
|:----------|:----------|:----------|
| amap_location_flutter_plugin   | [官网](https://lbs.amap.com/dev/demo/flutter-loc#Android) [GitHub ](https://github.com/amap-demo/amap-location-flutter)   | 高德官方开发维护Flutter 定位插件,猜测目前(2020-08-26) 其它3D地图、搜索 功能插件在开发中,耐心等待  |
|amap_map_fluttify ![](https://img.shields.io/pub/v/amap_map_fluttify.svg)|[官网](https://pub.flutter-io.cn/publishers/fluttify.com/packages) [Pub](https://pub.flutter-io.cn/packages/amap_map_fluttify) [GitHub](https://github.com/fluttify-project/amap_map_fluttify)|非官方开发维护，支持定位、地图、搜索、导航等基本全部功能,社区版基本满足需求,有特殊需求使用付费专业版或联系作者定制,目前公司项目使用的是社区版|
| flutter_bmflocation ![](https://img.shields.io/pub/v/flutter_bmflocation.svg)|[官网](https://lbsyun.baidu.com/index.php?title=flutter/loc/guide/create) [Pub](https://pub.flutter-io.cn/packages/flutter_bmflocation)| 百度官方开发维护的百度定位插件
| flutter_bmfmap  ![](https://img.shields.io/pub/v/flutter_bmfmap.svg)|[官网](https://lbsyun.baidu.com/index.php?title=flutter/loc/create-project/configure) [Pub](https://pub.flutter-io.cn/packages/flutter_bmfmap)|百度官方开发维护的百度地图插件 



### IM部分

| 库名  | 链接  | 简介  |
|:----------|:----------|:----------|
| rongcloud_im_plugin   ![](https://img.shields.io/pub/v/rongcloud_im_plugin.svg) | [官网 ](https://www.rongcloud.cn/downloads)  [Pub](https://pub.flutter-io.cn/packages/rongcloud_im_plugin) [GitHub](https://github.com/rongcloud/rongcloud-im-flutter-sdk/blob/master/README.md) | 融云官方开发维护-无UI   |
| jmessage_flutter  ![](https://img.shields.io/pub/v/jmessage_flutter.svg)  | [官网](http://docs.jiguang.cn/jmessage/client/client_plugins/)  [Pub](https://pub.flutter-io.cn/packages/jmessage_flutter)  [GitHub](https://github.com/jpush/jmessage-flutter-plugin)| 极光官方开发维护-  <font color=red>***提供6种非Native平台插件***</font>  |

### 社会化分享部分

| 库名  | 链接  | 简介  |
|:----------|:----------|:----------|
| sharesdk_plugin    ![](https://img.shields.io/pub/v/sharesdk_plugin.svg)| [官网](https://www.mob.com/wiki/detailed?wiki=ShareSDK_for_Flutter&id=14) [Pub](https://pub.flutter-io.cn/packages/sharesdk_plugin)  [GitHub](https://github.com/MobClub/ShareSDK-For-Flutter)  | MobTech shareSDK 官方开发维护-<font color=red>***提供5种非Native平台插件***</font>    |
| jshare_flutter_plugin   ![](https://img.shields.io/pub/v/jshare_flutter_plugin.svg) | [官网](http://docs.jiguang.cn/jshare/client/client_plugins/) [Pub](https://pub.flutter-io.cn/packages/jshare_flutter_plugin)  [GitHub](https://github.com/jpush/jshare-flutter-plugin) | 极光分享官方开发维护-<font color=red>***提供Flutter、RN平台插件***</font>    |

### App推广部分

- App推广：免填邀请码安装
- 携带参数安装
- 深度链接(deeplink)
- 快速安装与一键拉起
- 先进App地推统计方案——地推活动考核、管理、奖惩的精确依据


| 库名  | 链接  | 简介  |
|:----------|:----------|:----------|
| openinstall_flutter_plugin   ![pub package](https://img.shields.io/pub/v/openinstall_flutter_plugin.svg) | [官网](https://www.openinstall.io/doc/flutter_sdk.html) [Pub](https://pub.flutter-io.cn/packages/openinstall_flutter_plugin)   | openinstall 官方开发维护--<font color=red>***提供7种非Native平台插件***</font>    |
| jmlink_flutter_plugin   ![](https://img.shields.io/pub/v/jmlink_flutter_plugin.svg) | [官网](https://docs.jiguang.cn//jmlink/client/client_plugins/)  [Pub](https://pub.flutter-io.cn/packages/jmlink_flutter_plugin) [GitHub](https://github.com/jpush/jmlink-flutter-plugin) | 极光魔链官方开发维护-<font color=red>***提供Flutter、RN平台插件***</font>    |
| moblink ![](https://img.shields.io/pub/v/moblink.svg)|[官网](https://www.mob.com/wiki/detailed/?wiki=MobLink_for_Flutter&id=34) [Pub](https://pub.flutter-io.cn/packages/moblink) [GitHub](https://github.com/MobClub/MobLink-For-Flutter)| MobTech官方开发维护-<font color=red>***提供4种非Native平台插件***</font>

### 统计部分

| 库名  | 链接  | 简介  |
|:----------|:----------|:----------|
| janalytics   ![](https://img.shields.io/pub/v/janalytics.svg)| [官网](https://docs.jiguang.cn//janalytics/client/client_plugins/) [Pub](https://pub.flutter-io.cn/packages/janalytics) [GitHub](https://github.com/jpush/janalytics-flutter-plugin)   | 极光统计官方开发维护-<font color=red>***提供5种非Native平台插件***</font>    |
|||
| UMCAnalytics   | [官网](https://developer.umeng.com/docs/119267/detail/174923)    | 友盟官方开发维护-<font color=red>***仅提供Flutter平台插件***</font>     |
|flutter_growingio_track ![](https://img.shields.io/pub/v/flutter_growingio_track.svg)|[官网](https://docs.growingio.com/docs/developer-manual/sdkintegrated/otherframe-sdk/flutter-sdk) [Pub](https://pub.dev/packages/flutter_growingio_track) [GitHub](https://github.com/growingio/flutter-growingio-track)| GrowingIO平台官方开发维护-<font color=red>***提供6种非Native平台插件***</font> 

### 认证部分

- 整合了三大运营商的网关认证能力，为开发者提供了一键登录和号码认证功能，优化用户注册/登录、号码验证的体验，提高安全性

| 库名  | 链接  | 简介 |
|:----------|:----------|:----------|
| jverify   ![](https://img.shields.io/pub/v/jverify.svg) | [官网](https://docs.jiguang.cn//jverification/client/client_plugins/)  [Pub](https://pub.flutter-io.cn/packages/jverify) [GitHub](https://github.com/jpush/jverify-flutter-plugin)  | 极光认证官方开发维护-<font color=red>***提供4种非Native平台插件***</font>    |

### 支付部分

| 库名  | 链接  | 简介  |
|:----------|:----------|:----------|
| fluwx   ![](https://img.shields.io/pub/v/fluwx.svg)  | [Pub](https://pub.flutter-io.cn/packages/fluwx)  [Github](https://github.com/OpenFlutter/fluwx)  | 三方开发维护-包含微信分享(含小程序)、登录、支付功能 如果想单独使用分享登录、支付也有对应库    |
| flutter_alipay    ![](https://img.shields.io/pub/v/flutter_alipay.svg)   | [Pub](https://pub.flutter-io.cn/packages/flutter_alipay)  [Github](https://github.com/best-flutter/flutter_alipay)  | 三方开发维护的支付宝支付插件   |
