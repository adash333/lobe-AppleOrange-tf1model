# lobe-AppleOrange-tf1model

Microsoftの機械学習アプリLobe(beta版)を用いてリンゴとみかんの分類をWindowsのローカル環境で行ったものです。

[Microsoftの機械学習アプリLobe(beta版)でリンゴとみかんを分類するWEBアプリ作成を試してみる（１）LobeのインストールからTensorFlowモデルのエクスポートまで](https://i-doctor.sakura.ne.jp/font/?p=44635)

[Microsoftの機械学習アプリLobe(beta版)でリンゴとみかんを分類するWEBアプリ作成を試してみる（２）Windows10でPython3.6+TensorFlow1.15をセットアップ](https://i-doctor.sakura.ne.jp/font/?p=44703)

[Microsoftの機械学習アプリLobe(beta版)でリンゴとみかんを分類するWEBアプリ作成を試してみる（３）Windows10ローカル環境でtf_example.pyを実行](https://i-doctor.sakura.ne.jp/font/?p=44808)

## 実行方法

`git clone https://github.com/adash333/lobe-AppleOrange-tf1model.git`

Run `cd example` 

Run `pipenv --python 3.6` to setup virtual environment python 3.6

Run `pipenv shell`

Run `pipenv install`

Run `python tf_example.py 001.jpg` to predict.

example/001.jpgを、他のリンゴやみかんの画像に変更することにより、他の画像もpredictすることができます。

## 開発環境

```
Windows 10 Pro
VisualStudioCode 1.50
Git for Windows v2.29.2
python 3.6
pipenv 2020.8.13
```
