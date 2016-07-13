---
layout: post
title: First Posts
---

AndroidでGPSロガーを作る
#目次

- 目的
- 仕様
- 工程
- 完成品
- 参考

#目的
Android機にてGPS情報を取得し50人分のある地域での行動範囲を分析する。ちなみに今回が初のAndroidアプリ製作。

#仕様
・GPSログを取る
・DBには内部にRealmと外部にParse.comの２つを準備

#工程
##GPS情報を取得
GPS情報を取得するにはGPSを利用する方法とネットワークを利用する方法がある。

android.locationパッケージを利用する。

実装するのは
・LocationManagerクラス
・LocationListenerインターフェース
・Locationクラス
・LocationProviderクラス
の４つ。

##Realmを導入。GPSを記録する。
##Parse.comを導入。GPSを記録する。

#完成品

#参考
・Realm導入
：( http://qiita.com/wasabeef_jp/items/92bb700e37a0a57fc765 )
・GPS情報取得
：( http://www.adakoda.com/android/000125.html )
：(http://qiita.com/yasumodev/items/5f0f030f0ebfcecdff11)
