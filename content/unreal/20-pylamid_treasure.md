+++
title = "Pylamid Trasure"
date = 2026-02-08
summary =  "ジャンル:　3Dアクションゲーム\nプレイ人数:　1人\n開発時期:　2026年2月（2日間）\n開発人数:　1人"
featured = true
weight = 1
tags = ["3D", "アクション", "チーム開発"]
categories = ["ゲーム"]
main_image = "images/pylamid_treasure.gif"
intro_title = "開発概要"
intro_summary = "・ ゲームジャンル：　3Dアクションゲーム\n・ プレイ人数：　　 1人\n・ プラットフォーム：　Windows\n・ 開発人数：　　  1人\n・ 開発時期：　　  2026年2月（2日間）\n・ 開発ツール：　　  Unreal Engine"

main_demo_title= "▼プレイ動画"
main_demo = "https://www.youtube.com/embed/4hBxp0evi58?si=AHYIoRE8UmGfMizt"

+++


## ゲーム概要
[YouTubeのチュートリアル動画](https://unityroom.com/games/sakuraworld) を参考に、簡単な3Dアクションゲームを開発しました。
遺跡の舞台でコインを拾いつつ、出口を目指すゲームです。

## ゲームフロー
1. 遺跡のエリアへ侵入。
2. コインを拾いつつ、扉を開けるためのボタンを探す。
3. 木箱で隠された隠し通路を見つける。
4. 進んだ先の部屋にあるボタントラップを踏む。
5. トラップを踏むと扉が開くのでそちらに向かう
6. コインを拾いつつ、出口に向かうとクリア。

## 実装機能(全て担当)
※動作周りはブループリントを使用して実装しています。
- ランドスケープ、フォリッジを使用した地形作成
- コインの当たり判定と獲得機能
- コイン獲得数表示機能
- Collisionを使用したボタンオブジェクト押下機能
- カメラ遷移
- レベルシーケンスを用いた扉アニメーション
- 部屋の明かり実装(PointLightやDirectionalLightなど)
- SE、BGM