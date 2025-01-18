# 概要
入力値、重み、活性値をバイナリ化したCNNをPytorchで学習させ、推論をFPGAに実装した。<br>
データセットはMNISTを用いた。<br>
Pythonディレクトリでモデルの学習とハードウェア実装用のパラメータデータファイルの生成を行う。
# 参考文献
- BinaryNet	  https://arxiv.org/pdf/1602.02830v1.pdf
- Qiita       https://qiita.com/Surumechaninjp/items/85912e57cc1681cbe1f8

# コマンド
```
$ git clone git@github.com:nk12U/BinaryCNNonFPGA.git
$ docker-compose up --build -d
$ docker exec -it BinaryCNNonFPGA /bin/bash
```
