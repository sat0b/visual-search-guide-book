# PythonとTensorFlowで作る類似画像検索

このリポジトリは技術書典11で頒布した「PythonとTensorFlowで作る類似画像検索」 のサンプルコードと正誤表を管理するリポジトリです。

## サンプルコード

`/notebooks`以下にコードを置いています。

また、Colaboratory上にもnotebookのサンプルコードを置いています。

* 3章
  * https://colab.research.google.com/drive/1FcK2piUUuNnwiVANeLcu6REImpVCyD1J
* 4章
  * https://colab.research.google.com/drive/1m0FwEVY1DPk3CfBvgJqMHQ_oYY9K52Ja
* 5章
  * https://colab.research.google.com/drive/1KXXJdogdmx67pAtpT4ygA2-USD4RsTa8
* 6章
  * https://colab.research.google.com/drive/1tZ_PfcfufEd1IQdzZRpf5EQzl6dHbBfQ

## 正誤表

初版ではバージョン指定ができていなかったので、パッケージインストール時にバージョン指定をお願いします。
特にmiraが0.5から大きな変更があったため、指定が必要になります。

| ページ | 該当箇所 | 変更 |
|:--- |:--- |:---|
| ページ 48 | `!pip install pexels-api` | `!pip install pexels-api==1.0.1` |
| ページ 51 | `!pip install mira` | `!pip install mira==0.4` |
| ページ 54 | `!pip install keras_facenet` | `!pip install keras_facenet==0.3.2` |
| ページ 62 | `!pip install annoy` | `!pip install annoy==1.17.0` |
