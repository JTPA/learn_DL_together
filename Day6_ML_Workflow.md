# JTPA みんなでやろうDL オンライン勉強会 Day 6

Date: 8/20/2020 (Wed) 8PM

Venue: Hangout Meet (meetup参加者あてに通知されます）

Chat: [https://nocnoc.ooo/app#/chat/A1B6CDAC-637F-4455-9582-D086AC289268](https://nocnoc.ooo/app#/chat/A1B6CDAC-637F-4455-9582-D086AC289268)

<br>

## 当日資料

> [当日のスライド (Day6 前半)](https://docs.google.com/presentation/d/1GWjZRoPcZN15aQacPMnmXTN-gkZdfmISbboIKgxuhDs/edit?usp=sharing)

> [当日のスライド (Day6 パネルディスカッション用)](https://docs.google.com/presentation/d/1rx0nUcL5VbwJe_wnKiB4YUmJriybo5x-oWLt1vBQQNA/edit?usp=sharing)


<br>
  
## GAN

__DCGAN__

"[Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks](https://arxiv.org/pdf/1511.06434.pdf)” by 2016

元々あったGANの手法にDLを付け加えて今までにない複雑な画像の生成に成功した論文。

"Adversarial(敵対的)"と名前がつけられるように、ネットワークが二つの部分に分かれていてそれぞれが相反する目標に向かって最適化されるところがポイント。

<BR>

__SRGAN__

"[Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network](https://arxiv.org/abs/1609.04802)" by 2017

GANの手法を単眼超解像（低解像度の入力画像から高解像度の画像を生成する）タスクへ応用した論文。

ただGANの手法をGeneratorの最適化に使っただけではなく、Perceptual Lossを使ってより人の目で見て自然な画像の生成を行う他、
メインのアーキテクチャにResNetを使ったりアップサンプリングにおいてPixel Shufflerというアーティファクトの出にくいものを提案しているなど非常に画期的な論文。

<BR>

## Pose Machine

“[Convolutional Pose Machines](https://arxiv.org/pdf/1602.00134.pdf)” 2016

現在広く使われている、画像内の人物の姿勢を推定する技術の走りとなった論文。CMUの金出先生が名を連ねている。

全体的な印象としては既存の姿勢推定技術を多層のCNNで置き換えたことで大幅な精度向上があったと言える。
ただしそれだけではなくて、姿勢推定のタスクを3層に分けているところが大きなポイント。それぞれの層の出力（中間出力）をlossに加えることでレイヤー数が増えても学習できるようにし、
また周囲の他の部位の中間推定結果も踏まえてより高度な推定ができる構造になっている。

<BR>

## Anomaly Detection

[Anomaly Detection with Autoencoders Made Easy](https://towardsdatascience.com/anomaly-detection-with-autoencoder-b4cdce4866a6)


<BR>
  
## 特別ゲスト: [Daichi Yoshikawa](https://www.linkedin.com/in/daichi-yoshikawa-profile/), [Eiji Hayashi](http://eiji.hayashi.io/), [Yoshihiko Suhara](https://yoshi-suhara.com/) 

後半はML業界の一線で活躍されている上記特別ゲスト＋JTPAのスタッフ（西田、山中）のファシリテートによるパネルディスカッションでした。
最終回に相応しく、最先端のエンジニア／リサーチャーによる本音トークで大変盛り上がり参考になる会でした。ご参加頂いたゲスト・参加者の方には改めてお礼申し上げます。

[当日のスライド (Day6 パネルディスカッション用)](https://docs.google.com/presentation/d/1rx0nUcL5VbwJe_wnKiB4YUmJriybo5x-oWLt1vBQQNA/edit?usp=sharing)



