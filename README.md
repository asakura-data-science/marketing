# マーケティングデータ分析
# （Pythonによるビジネスデータサイエンス 第3巻）

<img src="https://www.asakura.co.jp/goods_img/118341.jpg" width="200px" >

---

本リポジトリは朝倉書店発行書籍『[マーケティングデータ分析](https://www.asakura.co.jp/books/isbn/978-4-254-12913-7/)』
（[Pythonによるビジネスデータサイエンス](http://www.asakura.co.jp/G_11.php?sreiesname=349) 第3巻）のサポートサイトです。

サンプルコードの解説については本書籍をご覧ください。
<br/>※本リポジトリに関する更新履歴は[wikiページ](https://github.com/asakura-data-science/marketing/wiki)をご参照ください。

---

## 1. サンプルプログラム

### 1.1. ファイル構成

サンプルプログラムはjupyter notebook(もしくはjupyter lab)で動作するipynbの形式で配布しています。
以下に示す実行環境の構築を参考にコードを実行してください。
既にPythonの実行環境が構築されているGoogle Colaboratoryによる実行も可能です。

|フォルダ名   |説明  |
|:--          |:--   |
|`Chapter_3`  |3章「集計と可視化からデータを理解する」で使用するデータと`.ipynb`形式のノートブック   |
|`Chapter_4`  |4章「顧客の分析」で使用するデータと`.ipynb`形式のノートブック   |
|`Chapter_5`  |5章「商品の分析」で使用するデータと`.ipynb`形式のノートブック   |
|`Chapter_6`  |6章「店舗の分析」で使用するデータと`.ipynb`形式のノートブック   |


## 2. 実行環境の構築と実行方法

#### 2.1. 実行環境の構築

最も簡単に実行したい方はGoogle Colaboratory（以下Colabと呼ぶ)の使用を検討してください。
本書のまえがきではDockerコンテナの利用を推奨していましたが，
本書の発売前にColabによる動作確認を行いました。
ColabはGoogleが提供するクラウドのPython実行環境で，
ブラウザからPythonコードが実行できます。
それ以外の方法で実行環境を構築したい場合は，本書のシリーズ「データの前処理」で公開されているGitHub
(https://github.com/asakura-data-science/preprocessing)
を参考にしてください。

以下では，Colabの利用を前提に説明します。

#### 2.2. Google ColabへのログインとGoogle Driveの連携
以前にColabにログインしたことがあり，Google Driveに「マイドライブ > Colab Notebooks」が作成されていれば「2.3.サンプルコードのダウンロード」に進んでください。
初めてColabにログインする方は、Colab (https://colab.research.google.com/notebooks/welcome.ipynb?hl=ja)
にアクセスします。
「Colaboratory へようこそ」というページが表示されていればファイルメニューから「ドライブにコピーを保存」
を選択してください。
これでGoogle Driveに「マイドライブ > Colab Notebooks」というフォルダが作成され，そこにファイルが保存されています。
本書で提供するプログラムとデータをこの場所に保存します。

#### 2.3. サンプルコードのダウンロード
本リポジトリのサンプルコードをPC環境にダウンロードします。
[こちら](https://github.com/asakura-data-science/marketing/archive/refs/heads/main.zip)
から本レポジトリのサンプルコード一式をダウンロードできます。
ダウンロードしたzipファイルを解凍すると「marketing-main」というフォルダができます。
名前を「marketing」に変更し，Google Drive (https://www.google.com/intl/ja_jp/drive/)
にそのフォルダを保存します。プログラムから保存したデータを利用するので，
「マイドライブ > Colab Notebooks」に保存してください。
別の場所に保存することもできますが，その場合は本書提供プログラムの入力パスを変更する必要があります。

## 3. 実行方法
Colabに保存したプログラムを起動します。
ここでは，例としてGoogle Driveに保存したmarketing > Chapter_3 > 3_1.ipynbをダブルクリックで起動します。
起動したファイルを実行する場合はいくつか方法がありますが，例えば，ランタイムメニューの「全てのセルを実行」
を選択すると全てのコードが実行されます。
個別に実行したい場合は，実行したいセルにカーソルを併せて，矢印ボタンをクリックすることで実行できます。


## 4. 関連リンク集

### 4.1. 共通
- Python: https://www.python.jp/
- pandas: https://pandas.pydata.org/
- jupyter: https://jupyter.org/
- NYSOL: https://www.nysol.jp/
- Docker: https://www.docker.com/     &emsp;(日本語サイト) https://docs.docker.jp/

### 4.2. データ関連
- QPR: https://www.macromill.com/service/database_research/qpr.html
- Yakiniku: https://c032802.gorp.jp/
- KOHYO: https://www.kohyo.co.jp/

