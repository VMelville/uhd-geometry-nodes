# UHD Geometry Nodes

Blenderの Geometry Nodes を使用した物体検出モデルの実装です。

## 概要

このプロジェクトは、PINTO氏による軽量な物体検出モデル **UHD** を Blender Geometry Nodes に統合したものです。

## 利用技術

- **UHD（物体検出モデル）**: [PINTO0309/UHD](https://github.com/PINTO0309/UHD)（MIT License）
- **モデルバリアント**: `ultratinyod_res_anc8_w16_64x64_opencv_inter_nearest_static.onnx`
- **テクスチャ**: ONNX から抽出した重みを TIFF テクスチャ化したもの

## 使用方法

### 動作確認

Blender 5.0 以降でプロジェクトファイル（`.blend`）を開くことで動作を確認できます。

## データ出典

- **サンプル画像**: [Tokyo Railway Station](https://commons.wikimedia.org/wiki/File:Tokyo_Railway_Station._(44436526580).jpg)（パブリックドメイン）
  - `image/` ディレクトリ以下に配置されているサンプル画像は、上記のパブリックドメイン画像を正方形にトリミング・リサイズしたものです。

## ライセンス

本プロジェクトで使用している UHD は MIT License の下で提供されています。
