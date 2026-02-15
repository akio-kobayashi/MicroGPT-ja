# MicroGPT 日本語教材版

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akio-kobayashi/MicroGPT-ja/blob/master/MicroGPT_ja_colab.ipynb)

- Colabで開く: https://colab.research.google.com/github/akio-kobayashi/MicroGPT-ja/blob/master/MicroGPT_ja_colab.ipynb

このディレクトリは、Andrej Karpathy 氏の MicroGPT（最小構成の GPT 実装）を学習用に扱うための補助資料です。

- オリジナル実装: `microgpt.py`
- 日本語教材ノートブック: `MicroGPT_ja_colab.ipynb`

## 目的

この内容は **教育利用** を目的としています。  
実運用や高性能化を目的とした実装ではなく、以下を理解するための教材です。

- 文字単位トークナイザ
- 自動微分（計算グラフと逆伝播）
- Transformer/GPT の最小構成
- 学習ループと生成

## 謝辞

本教材は Andrej Karpathy 氏の公開実装に基づいています。  
原著作者およびオリジナルプロジェクトに感謝します。

- Original source: https://gist.github.com/karpathy/8627fe009c40f57531cb18360106ce95
- Author: @karpathy

## 日本語ノートブックの内容

`MicroGPT_ja_colab.ipynb` には以下を含みます。

1. 日本語コメントによる初学者向け解説
2. 外部データ不要の日本語サンプル（self-contained）
3. 学習時の損失可視化
4. 推論時の次トークン確率可視化

## 実行方法（Google Colab）

1. `MicroGPT_ja_colab.ipynb` を Colab で開く
2. 上から順にセルを実行
3. 学習損失グラフと生成結果を確認

## 注意

- 教材向けに小さなモデル設定です。
- 出力は毎回ランダム要素を含みます（乱数シードは固定）。
