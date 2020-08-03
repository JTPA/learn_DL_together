# JTPA みんなでやろうDL オンライン勉強会

* 全6回 隔週水曜日開催 (勉強会の次の週はフォローアップ用のもくもく会)
* 初心者向け （但し コードを書いてDLをしっかりマスターするつもりの方のみ）
* [Google Colab](https://colab.research.google.com/)を使ってオンラインでコードを実行し演習を行います
* 各回は前半45分と後半45分
* 前半は各種の基礎知識や基本DLアーキテクチャをJTPAのスタッフが実演／解説
* 後半はJTPAギークサロンライクに特別ゲストをお呼びして、より深い技術分野や旬の話題をご解説頂きます
* 勉強会は Hangout Meetを用いてオンラインでの配信／参加 参加は無料／自由入退出OK　ご飯食べながらやビール飲みながら聞くのもOK
* DLフレームワークは[Keras](https://keras.io/ja/)を使用
* 事前や事後の質問はissueを作って質問してもらうか、twitterにて [@Jiny2001](https://twitter.com/Jiny2001) と [@glory791days](https://twitter.com/glory791days) まで

<br>

勉強会開催後の次週はオンラインもくもく会です。自由にコードを書いて復習したり作ったものを皆に共有する時間として使って下さい。当日はJTPAスタッフが質問などにお答えします。

## 参加者管理 / 参加申請
https://www.meetup.com/JTPA-Japanese-Technology-Professionals-Association/

<br>

## Prerequisites / 参加のために必要なこと

本勉強会は皆が集まって勉強するのをJTPAスタッフ及び特別ゲストがサポートするというスタンスです。

Colabノートを使って理解した内容を適宜実行してML/DLの基本構造をよりよく理解することを目標としています。参加希望者数が多く、当日のスムーズな進行のために参加者様には事前に下記の確認をお願い致します。

0) __アンケート (ツールやMLに対しての事前知識の確認)__ Day1参加者は[みんなでやろうDLの会　初回前アンケート](https://forms.gle/zumyqq5Y3vX3TPt58) への記入をお願い致します
<br>

1) __Python の基本構文を理解しておく__　不安のある方は [Pythonの基本文法まとめてやんよ!!!](http://tokidoki-web.com/2016/02/python%E3%81%AE%E5%9F%BA%E6%9C%AC%E6%96%87%E6%B3%95%E3%81%BE%E3%81%A8%E3%82%81%E3%81%A6%E3%82%84%E3%82%93%E3%82%88/)
<br>


2) __Google Colab ノートでセルの実行の仕方を理解しておく__

　下記のColabノートを開くと物体認識のDLモデルを実行できるノートが開きます。

[Google EfficientDet](https://colab.research.google.com/github/google/automl/blob/master/efficientdet/tutorial.ipynb)

下記画像にしたがって 1.1 Inference a single image まで実行できることをご確認お願い致します。

[Google Colaboratory（グーグルコラボ）の 使い方](https://pyhoo.jp/google-colaboratory-manual)

| | |
|---|---|
|<img src="images/colab1.png" width="320">|<img src="images/colab2.png" width="320">|

<br>


## 当日利用する予定のツール

1) Hangout Meet (ミーティングURLは meetup.comにて参加予定者へ送付)

2) [イベント用チャットツール nocnoc (当日用のページ)](https://nocnoc.ooo/event/498A5C34-C242-4068-AC0C-4B06E168CFAB)
 (colabの実行についてやMLなどについての事前の質問はこちらへ)

3) [当日 進度確認／フィードバック用ツール CommentScreen ](https://commentscreen.com/comments?room=DL_together)

<br>

## Road map

|        | Date                | Title              | コースマテリアル             |特別ゲスト              |
|:------:|:-------------------:| :-----------------:|:-----------------:|:-----------------:|
| [Day 1](Day1_ML_Basic.md)  | 4/22/2020 (Wed) 9PM | ML/DLの基本原理を理解 |[TensorFlow, Keras and deep learning, without a PhD](https://codelabs.developers.google.com/codelabs/cloud-tensorflow-mnist/) 前半| [矢戸 知得](https://www.linkedin.com/in/chitoku-yato-01ba304/) 氏 (NVIDIA テクニカルマーケティング・マネジャー) |
| [Day 1.5](Day1_5_ML_Basic.md)  | 4/29/2020 (Wed) 9PM | 復習用 もくもく会|
| [Day 2](Day2_CNN_and_more.md)  | 5/6/2020 (Wed) 9PM | CNN / Dropout / 他各種テクニック |[TensorFlow, Keras and deep learning, without a PhD](https://codelabs.developers.google.com/codelabs/cloud-tensorflow-mnist/) 後半| [山下 力也](https://www.linkedin.com/in/rikiya-yamashita/) 氏 (スタンフォード大 Department of Biomedical Data Science ポスドク) |
| [Day 2.5](Day2_5_CNN_and_more.md)   | 5/13/2020 (Wed) 9PM | 復習用 もくもく会|
| [Day 3](Day3_RNN.md)   | 5/20/2020 (Wed) 9PM | RNN / 時系列データ処理 | [Illustrated Guide to LSTM’s and GRU’s](https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21) | [数原 良彦](https://yoshi-suhara.com/) 氏 (Megagon Labs リサーチサイエンティスト) |
| [Day 3.5](Day3_5_RNN.md)  | 5/27/2020 (Wed) 9PM | 復習用 もくもく会|
| [Day 4](Day4_Networks.md)  | 6/17/2020 (Wed) 8PM | 画像系 必須アーキテクチャ |  | [土田 安紘](https://awl.co.jp/member/yasuhiro-tsuchida/) 氏 (AWL株式会社 CTO / AI HOKKAIDO LAB所長)氏 |
| [Day 4.3](Day4_3_Networks.md)  | 6/24/2020 (Wed) 8PM | 復習用 もくもく会|
| [Day 4.6](Day4_6_Networks.md)  | 7/1/2020 (Wed) 8PM | 論文読み会 |
| [Day 5](Day5_RL_and_AutoML.md)    | 7/15 (Wed) 8PM | 強化学習、モデルの自動設計(AutoML) | | [飯塚 修平](https://tushuhei.com/)氏 (クリエイティブ テクノロジスト) |
| [Day 5.5](Day5_5_RL_and_AutoML.md)  | 7/22 (Wed) 8PM | 復習用 もくもく会|
| [Day 5.7](Day5_7_RL_and_AutoML.md)  | 7/29 (Wed) 8PM | 復習用 もくもく会 (PartII)|
| [Day 6](Day6_ML_Workflow.md)    | TBD (Wed) 8PM | ML開発ワークフロー | | TBD |
| [Day 6.5](Day6_5_ML_Workflow.md)  | TBD (Wed) 8PM | 復習用 もくもく会|

<br>

### Google Colab とは？

Googleの提供する無料のクラウドサービスです。

自分の書いたPythonコードをGoogleの提供するサーバーやGPUを利用して実行できるだけでなく、Linuxのコマンドを実行して自由にモジュールをインストールすることができ、さらには自分のコードをGoogle Driveに保存したり他人と共有することができる大変便利なサービスです。

[Google Colaboratory（グーグルコラボ）の 使い方](https://pyhoo.jp/google-colaboratory-manual)

[codExa.net Google Colabの知っておくべき使い方](https://www.codexa.net/how-to-use-google-colaboratory/)

### Keras とは？

DL用のPythonフレームワークあるいはライブラリです。TensorflowやTheanoといった他のDLライブラリをまとめて簡単に実行できる中間APIと考えて差し支えないと思います。

[Keras: Pythonの深層学習ライブラリ](https://keras.io/ja/)

<br>

## スタッフ：
山中 仁 / Google, Research Engineer [@Jiny2001](https://twitter.com/Jiny2001)

西田 祐木 / Waymo, Software Engineer [@glory791days](https://twitter.com/glory791days)

運営：[JTPA (Japanese Technology Professionals Association) ](https://jtpa.org/)

<br>

## 全体お役立ちリンク

__MLの基礎用語・知識に自信がない方のための事前必読署：__

[ 機械学習を学習する by Google Cloud （漫画で分かるマシンラーニング）](https://cloud.google.com/products/ai/ml-comic-1/?hl=ja)

[ 機械学習を学習する by Google Cloud （漫画で分かるディープラーニング）](https://cloud.google.com/products/ai/ml-comic-2/?hl=ja)


__画像認識や人体ポーズ推定など、各種のDLモデルがColab上でオンラインで気軽に試せるプロジェクト：__

[tugstugi/dl-colab-notebooks](https://github.com/tugstugi/dl-colab-notebooks)

__Jiny2001によるDL主要 論文リスト：__

[ディープラーニングの超基本論文まとめ](https://qiita.com/jiny2001/items/94081320ab1d92a20283)
