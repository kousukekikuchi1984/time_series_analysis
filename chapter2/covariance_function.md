---
title: "covariance function"
author: "kousuke kikuchi"
date: "April 12, 2015"
output: html_document
---

# 2. 共分散関数
- 定常な時系列の特徴を表現するための最も基本的な手法
    - 自己共分散関数は時系列の過去の変動と相関の強さを示す
    - 相互共分散関数は他の時系列の変動との相関の強さを示す
    - これらの関数はスペクトルの推定や時系列モデルの推定に用いられる
    
### 2.1 時系列の分布と定常性
- 平均値関数(mean value function)
    - 時系列y1, ...ynとするときのynの期待値
    - 時間nを変数にもつ関数
- 自己共分散(autocovariance)
    - 時系列$y_{n}$と時間kだけシフトした$y_{n-k}$との共分散
- 弱定常（weakly stationary, covariance stationary）
    - 平均値、分散、共分散が時間とともに変化しないモデル
    - 比較的簡単に分析可能
- 強定常（strongly stationary）
    - 時系列の分布が時間シフトに関し、不変であること
    
### 2.2 定常時系列の自己共分散関数
- 定常時系列系の平均値関数
    - 時系列に定常性を仮定すると、平均値関数は時間によらない一定の値になる
- 定常時系列系の自己共分散関数
    - 
