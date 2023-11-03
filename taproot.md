# Lightning Network & Taproot 
<div align="left">
<img src=https://upload.wikimedia.org/wikipedia/commons/thumb/7/7a/17_node_mesh_network.svg/1920px-17_node_mesh_network.svg.png width=30% />
</div>

## What is Lightning?
ライトニングネットワーク（英: Lightning Network）は、Bitcoinのチェーン上に構築(こうちく)された2層(そう)ネットワーク、つまりBitcoinのL2です。これは、ビットコインの拡張(かくちょう)性や取引手数料の高さの問題を解決するためのものです。このネットワークは、nodeとchannelで支払いネットワークを構築しています。

<div align="left">
<img src=https://pic3.zhimg.com/v2-32155a16c4d90153c5a4b33108e1d456_r.jpg width=30% />
</div>

* node：ネットワークに接続(せつぞく)されたコンピュータ機器など、ユーザーがそれを使って取引を開始するclientです。 
* channel：ノード間のネットワークルーティングといくつかの制約を設定し、このルーティングを介して支払い取引などの機能を実現します。 
* 決済(けっさい)：channelを閉じる前に、channel内の取引の状態をパッケージ化してbtc block chainにアップロードします。この取引は最終的にblockにパッケージ化され、変更不可能なbtc台帳(だいちょう)に保存されます。 

以上は簡単な業務の説明で、復雑な技術の実現には触れ(ふれ)ません。 

## Why use it?

## How to use it?

## Taproot on Lighting 
