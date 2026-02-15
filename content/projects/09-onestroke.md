+++
title = "3D一筆書き"
date = 2023-09-01
summary =  "ジャンル:　3Dパズルゲーム\nプレイ人数:　1人\n開発時期:　2023年9月～12月（4ヶ月）\n開発人数:　1人"
featured = true
weight = 0
tags = ["3D", "パズル", "XR", "HoloLens2", "個人開発"]
categories = ["ゲーム"]
main_image = "images/one_stroke_holo.gif"
intro_title = "開発概要"
intro_summary = "・ ゲームジャンル：　3Dパズルゲーム\n・ プレイ人数： 　　1人\n・ プラットフォーム：　Windows, HoloLens2 \n・ 開発人数：　　  1人\n・ 開発時期：　　  2023年9月～12月（4ヶ月）\n・ 開発ツール：　　  Unity (C#), MRTK, UniRx, UniTask"
+++

## ゲーム概要
卒業研究で実験のために開発した3Dの一筆書きです。
5ステージ連続で挑戦します。
PCとHoloLens2というXRデバイスの2プラットフォームで遊べます。

## 実装機能(全て担当)
- PC
  - マウス左クリック長押しで点と点を繋ぐ機能
  - カメラ移動
- HoloLens
  - 点との接触判定
- 最後に選んだ点を高速点滅、2番目に選んだ点をゆっくり点滅させる機能
- 通った線の色を変える機能
- 時間計測機能
- リセット機能
- [一筆書きオブジェクトをカメラ空間に投影した時の面積計算、テキスト書き出しツール](https://kyoka122.github.io/Profile/Profile/technical/rastarize/) 
- [点と線を生成するためのツール](https://kyoka122.github.io/Profile/Profile/technical/auto-generator/) 


## デモ動画
- HoloLens(外から見たとき)
- PC

