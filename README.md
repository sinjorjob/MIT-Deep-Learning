# MIT Deep Learning

<a href="https://deeplearning.mit.edu/"><img src="https://deeplearning.mit.edu/files/images/mit_deep_learning.png"></a>

このリポジトリは[MIT Deep Learningコース](https://deeplearning.mit.edu/)のチュートリアル(tutorial_deep_learning_basics)を日本語化＋補足情報を追記したリポジトリです。 

本家gitリポジトリはこちら(https://github.com/lexfridman/mit-deep-learning)

## Tutorial: Deep Learning Basics

このチュートリアルは、MIT Deep Learningの一部として提供される[Deep Learning Basicsの講義](https://www.youtube.com/watch?list=PLrAXtmErZgOeiKm4sgNOknGvNjby9efdf&v=O5xeyoRL95U)に付属しています。

YouTubeでビデオを見ることができます。

[![Deep Learning Basicsの講義](https://i.imgur.com/FfQVV8q.png)](https://www.youtube.com/watch?list=PLrAXtmErZgOeiKm4sgNOknGvNjby9efdf&v=O5xeyoRL95U)


MNISTデータセットを使ったディープラーニングの入門者向けのチュートリアルになっています。

最終的に学習したモデルに対してgitリポジトリ(tutorial_deep_learning_basics)のimages配下にある`mnist_dream.mp4`をインプットとして与えます。  

`mnist_dream.mp4`は以下のように手書き数字が動的に変化する動画になっています。

![MNIST dream](https://i.imgur.com/OrUJs9V.gif)

この動画をインプットにして１フレームごとに画像に切り出し、学習したモデルにインプットして推論結果を得ます。
推論結果を画像に追加して再度動画に変換すると以下のような推論結果付きの動画が生成されます。

![MNIST dream predictions](https://i.imgur.com/eMF9FOG.gif)

