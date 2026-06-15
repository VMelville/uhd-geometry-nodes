# UHD Geometry Nodes

Blenderの Geometry Nodes を使用した物体検出モデルの実装です。

PINTO氏による軽量な物体検出モデル **UHD** が実装されています。

<img width="2560" height="1604" alt="image" src="https://github.com/user-attachments/assets/f8d7f6b5-e176-425e-ad53-0f04b94c8855" />

## 利用モデルについて

- **UHD（物体検出モデル）**: [PINTO0309/UHD](https://github.com/PINTO0309/UHD)（MIT License）
- 利用したバリアントは `ultratinyod_res_anc8_w16_64x64_opencv_inter_nearest_static.onnx`
- ONNX から抽出した重みを TIFF テクスチャ化し、texturesフォルダ以下に格納しています。

## 実行方法

Blender 5.0 以降でプロジェクトファイル（`.blend`）を開くことで動作を確認できます。

## サンプル画像について

[Tokyo Railway Station](https://commons.wikimedia.org/wiki/File:Tokyo_Railway_Station._(44436526580).jpg)（パブリックドメイン）

`image/` ディレクトリ以下に配置されているサンプル画像は、上記の画像を 2048 × 2048 px にトリミング・リサイズしたものです。

## ライセンス

MIT License
