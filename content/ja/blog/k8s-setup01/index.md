---
title: "Raspberry Pi 4 で Kubernetes クラスタを構築"
date: 2020-01-23T03:23:21+09:00
---

### はじめに
昨年2019年の秋ごろにとあるコンテストの賞金として25,000円が手に入ったので、思い切ってRaspberryPi4の4GBモデルを３台購入しました。

そこで、以前からKubernetesとラズベリーパイを使用したクラスタが気になっていたので、これを機に構築することにしてみました。

## セットアップ（ソフト）
具体的なセットアップの方法は[こちら](https://github.com/Takahiro55555/ShellScripts/tree/master/RaspiK8s)に書きました。

### 外見
以下の画像のような外見で運用中です（笑）。
[ケース](/projects/raspi-honeycomb-case)やファンガードはFusion360でモデリングし、3Dプリンタで出力しました。

![システムの全体像（冷却ファン無）](no_funs.JPG)
![システムの全体像（冷却ファン有）](exist_funs.JPG)