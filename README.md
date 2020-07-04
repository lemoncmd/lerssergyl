# 拡張機能「リパライン語ツール」

## Downloads
Chrome： [リパライン語ツール – Chrome ウェブストア](https://chrome.google.com/webstore/detail/%E3%83%AA%E3%83%91%E3%83%A9%E3%82%A4%E3%83%B3%E8%AA%9E%E3%83%84%E3%83%BC%E3%83%AB/ebakbifgbdhdkhmalcjjbgmfifciobdn?hl=ja&authuser=0)

Firefox： [リパライン語ツール – 🦊 Firefox (ja) 向け拡張機能を入手](https://addons.mozilla.org/ja/firefox/addon/%E3%83%AA%E3%83%91%E3%83%A9%E3%82%A4%E3%83%B3%E8%AA%9E%E3%83%84%E3%83%BC%E3%83%AB/)

![](http://jurliyuuri.org/wp-content/uploads/2020/06/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88-202-768x480.png)

## Usage
まず、好きなウェブページで読みたいリパライン語の文章をマウスで選択します。

![](http://jurliyuuri.org/wp-content/uploads/2020/06/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88-211-1.png)

そして、ブラウザの右上にある拡張機能アイコンをクリックします。

![](http://jurliyuuri.org/wp-content/uploads/2020/06/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88-213.png)

すると、拡張機能のポップアップ画面が表示されます。

![](http://jurliyuuri.org/wp-content/uploads/2020/06/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88-215-768x480.png)


再生ボタンをクリックすると、そのリパライン語文章が合成音声を用いて再生されます。
また、各単語のアコーディオンメニューをクリックすると、その単語の形態素ごとの意味が辞書から参照されテーブル表示されます。

![](http://jurliyuuri.org/wp-content/uploads/2020/06/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88-217-768x479.png)

また、最初に選択された誤解釈であった場合、検索候補の欄で分解候補を選択することで合った解釈を選ぶことができます。

## Option
リパライン語ツールの画面にある歯車アイコンをクリックすると、オプション画面が表示されます。

![](http://jurliyuuri.org/wp-content/uploads/2020/06/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88-218-768x480.png)

ここでは、

- リパライン語ツールをリパーシェ(リパライン語の文字)で表示するかどうか
- 廃止された緩衝子音(発音しやすくするための子音)を分解に用いるかどうか
- 文章を読み上げる速度(wpm: words per minute 1分間に読み上げる単語数)

を設定することができます。

## Contribution
リパライン語ツールの要望やバグ等は、本リポジトリの[Issues](https://github.com/lemoncmd/lerssergyl/issues)にお願いします。  
また、合成音声の不具合につきましては、そちらの[Issues](https://github.com/lemoncmd/espeak-ng/issues)にお願いします。

## License
合成音声部分：GPL 3.0(改変したespeak-ngを動的に参照しています)  
単語分解器：Copyright (c) sozysozbot  
リパライン語辞書：Copyright (c) Fafsfalira  
フォント：Copyright (c) S.Y  
その他：Copyright (c) lemoncmd  
リバースエンジニアリングは許可しますが、ソースコードについては各ライセンスに従います。

## Special Thanks
- リパライン語単語分解器開発者のJekto.vatimeliju氏
- リパライン語作者のFafs.F.Sashimi氏
- フォント作成者のFalira.lyjotafis氏
- リパライン語OTM-JSON辞書管理者のskurlavenija.hortxertiju氏
- その他開発用ツール製作者各位
