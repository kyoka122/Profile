+++
title = "3D一筆書きゲームの作成補助ツール"
date = 2024-01-05
summary = "3D一筆書きを作成するため、点と点(球と球)を結ぶ線(円柱)オブジェクトを自動で配置する簡易ツールを作成。\n開発人数:　1人\n開発時期:　2023年月~月(ヶ月)"
featured = true
weight = 2
tags = ["ツール", "個人開発"]
categories = ["ツール"]
main_image = "images/one_stroke_tool.gif"
intro=""

main_demo_title= "▼プレイ動画"
main_demo = "https://www.youtube.com/embed/Fs8_OF9j79k?si=cCA4OHCPgc2xQgT6"

+++

## ツール概要
ステージ作成のツールをエディタ上で利用したかったため、EditorのOnInspectorGUI()で各種機能を実装したツールになります。
- 点(球)の生成
- 点(球)の番号を2つ指定して生成ボタンを押すと、2つの点を結ぶ線(円柱)を自動で生成する。（点を後で動かした際の更新も可）
- 点、線の削除機能

## 実装Step
- [[🔗コード]](https://github.com/kyoka122/SquareCalculation/blob/4ca696a9018221dbd1064a5c0cf98f163a3a2420/Assets/Scripts/Editor/AutoInstanceEditor.cs#L112)　点、線の更新、削除のために、各オブジェクトをリストを使って管理している。そのリストへの動的登録機構。
- [[🔗コード]](https://github.com/kyoka122/SquareCalculation/blob/4ca696a9018221dbd1064a5c0cf98f163a3a2420/Assets/Scripts/View/ObjectsRegistrant.cs#L94
)　定位置に点を生成
- [[🔗コード]](https://github.com/kyoka122/SquareCalculation/blob/4ca696a9018221dbd1064a5c0cf98f163a3a2420/Assets/Scripts/View/ObjectsRegistrant.cs#L303)　2つの球位置関係から円柱のposition,rotation,scale(円柱の長さ)を導出
