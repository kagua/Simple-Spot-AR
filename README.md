# Simple-Spot-AR
 JavaScriptだけで動作するシンプルな地点ARです。

![Screenshot_20231218-220830](https://github.com/kagua/Simple-Spot-AR/assets/631291/cb8728d9-87fc-44d1-9b30-7c4b5ced09bd)

## オープン音声AR「シンプルスポットAR」

とにかくシンプルに実装できる地点ARを作りました。サーバーにHTMLファイルと、その地点で動作させたい画像や音声や動画を連動させるだけで、とりあえずスポットガイド的には使えると思います。GPS精度はブラウザ由来なのであまり期待しないでください。

**現在地を取得して特定地点との距離を表示するJavaScript**

https://www.kagua.biz/tool/javascript-tool/20231219a1.html

## サンプル

渋谷のハチ公の緯度経度をあらかじめセットしてあります。ハチ公像の近く20m以内でタップしますと、「ビンゴ！」とメッセージが出て、サンプルボイスが自動的に流れます。

それ以外ですと、誤差をmで表示してくれます。

**ハチ公銅像までの距離**

https://www.kagua.biz/panpan/

## 仕組み

JavaScriptで緯度経度を取得

指定の緯度経度との距離を算出

差が20メートル以内なら、サンプルMP3を自動再生

2023年12月19日
