# DFPlayerProUNIT

<img src="https://github.com/akita11/DFPlayerProUNIT/blob/main/DFPlayerProUNIT.jpg" width="240px">

<img src="https://github.com/akita11/DFPlayerProUNIT/blob/main/DFPlayerProUNIT_with_Pro.jpg" width="240px">

DFRobotの音声プレーヤモジュール[DFPlayer Pro](https://www.switch-science.com/products/8005)をGrove端子を接続して制御できるモジュールです。Grove端子からシリアル(UART)通信で音声再生などを制御することができます。（UIFlow(v1)用のブロックも用意する予定）

※DFPlayerProは付属していません


## 使い方

<img src="https://github.com/akita11/DFPlayerProUNIT/blob/main/DFPlayerProUNIT_terminal.jpg" width="240px">

以下のようにスピーカやアンプを接続し、Grove端子からの制御で音声を再生します。また基板上の"PAYE"と"KEY"のシルクが示されている2組の端子は、それぞれDFPlayerProのKEY、PLAY端子に接続されていますので、これらを使って再生を制御することもできます（詳細はDFPlayerProのマニュアルを参照してください）

### アンプ付きスピーカに接続する場合

3.5mmジャック（ステレオ：上部中央）に3.5mmステレオケーブル等でアンプに接続します。


### スピーカを直接接続する場合

本体上部の2つの2.54mmた端子にスピーカを接続します。spkLとspkRがそれぞれお左と右のスピーカです。基板中央部に1.25mmピッチコネクタ(Molex 53047-0210用)をとりつける端子があり、市販の小型スピーカ（M5Stack本体に使われているものなど。AliExpressやTaobaoでも同等品があります）を接続することができます。


### 3.5mmジャックに直接スピーカを接続する方法

3.5mmジャックに直接スピーカを接続することもできます。その場合は、基板裏面のハンダジャンパを以下のように修正してください。

<img src="https://github.com/akita11/DFPlayerProUNIT/blob/main/DFPlayerProUNIT_back.jpg" width="240px">

- JP1をカット
- JP2・JP3の中央と△マーク側をカットし、中央と反対側（△マークがない側）をショート


## Author

Junichi Akita (@akita11) / akita@ifdl.jp
