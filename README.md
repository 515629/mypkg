# mypkg
こちらは千葉工業大学未来ロボティクス学科のロボットシステム学２０２３の授業で製作したものです

![test](https://github.com/515629/mypkg/actions/workflows/test.yml/badge.svg)

* ROS2のインストールがまだの方は先にインストールをお願いします
* ROS2のインストールがお済の方は下記のコードでクローンを行ってください
```
$ git clone https://github.com/515629/mypkg.git
```

## talker.py
* 数字をカウントして、トピック/countupを通じてメッセージを送信するパブリッシャを持つノードです
	* メッセージの型は16ビット符号つき整数です

## listener.py
* /countupからメッセージをもらって表示するサブスクライバを持つノードです

## talk_listen.launch.py
* talker.pyとlistener.pyを一度に立ち上げることができます

## 実行方法と結果
#### 端末を2つ使う場合

## 必要なソフトウェア
* ROS2（作成者の使用バージョン : humble）

## テスト環境
* Ubuntu 22.04.2 LTS

## ライセンス
* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます
* このパッケージのコードは、Ryuichi Ueda氏の以下のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）を参考に、本人の許可を得て自身の著作としたものです
	* [ryuichiueda/my_slides/robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
* © 2023 Jun Tokoeda
