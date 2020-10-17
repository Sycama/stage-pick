# スマブラSPステージピックツール

スマブラの大会でのステージピックの様子を配信に映したいときに使えそうなツールを作りました！導入法についての詳しい説明は気が向いたら書きます！

多分アレンジとかもそんなに難しくないと思うので，これを元に各自に合わせて細かいところをいじってもらえればと思います．

おかしなところがあったら[製作者のTwitter](https://twitter.com/Sycama_ssb)までどんどん指摘してください！質問ももちろん歓迎です！

## 必要なもの
### 絶対必要なもの
- [NodeCG](https://nodecg.com)の環境

どうやらしょっちゅう導入方法が変わるらしく？日本語で導入方法を説明している記事は参考になったりならなかったりします．  
公式サイトに載っている方法が1番楽だと思うので，基本的には，[このページ](https://nodecg.com/docs/installing)を見て導入すればいいのかなと思います．

### 場合によって必要なもの(だいたい不必要)
- [ngrok](https://ngrok.com)

## 使い方
### 基本的な使い方
このフォルダをNodeCGの`bundles`フォルダに入れて，NodeCGを実行するだけ．

### ステージピックをタブレット端末や他のPC上で行うためには
NodeCGはlocalhost上で動いているので，ただ実行しただけの状態だと，NodeCGを実行しているPC上でしかステージピックが行えません．  
オフ大会などでは，参加者にそのPC前まで来てもらってステージピックを行う，というのはなかなか難しいと思います．そこで，他の端末にステージピック画面を映す必要があります．

#### ステージピック画面を映す端末とツール実行中PCを同じルータに接続することができる場合

ツール実行中PCのIPアドレス(IPv4)を調べ，`http:<IPアドレス>:9090`にアクセスするだけ．  
大抵は`http:192.168.x.xxx:9090`みたいなアドレスだと思います．

#### 同じルータに接続できない場合

オンライン大会や，特殊な環境でのオフライン大会などで当てはまると思います．  
その場合は[ngrok](https://ngrok.com)を使ってください．  
導入はまあまあ面倒くさいので注意してください．

また，これを使うとURLを知っている人全員がステージピック画面にアクセスできるようになってしまうので，オンライン大会などでは何かしらのひと工夫が必要かもしれないです．  
というかこれ以外にも多分方法あるので，他の方法を使ったほうがいいかもです．

## Licence

Copyright (c) 2020 Sycama  
This software is released under the MIT License, see LICENSE.txt.


## Author

Sycama  
Twitter: [@Sycama_ssb](https://twitter.com/Sycama_ssb)