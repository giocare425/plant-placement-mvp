# 観葉植物お試し配置サービス MVP v3.3

## 修正内容

ver.3.2ベースで以下を修正。

- 導線を変更
  - 1. 植物を選ぶ
  - 2. 部屋写真をアップロード
  - 3. 配置・サイズ調整
  - 4. 診断結果
- ②植物選択カードの小さいアイコンを assets の写真画像に変更
- ③配置・サイズ調整の植物も assets の写真画像に固定
- fallback SVG（イラスト）参照を表示側から除去
- 対象植物は4種のみ
  - モンステラ
  - ケンチャヤシ
  - フィカス・ウンベラータ
  - ポトス

## 必要なassets

既存の assets フォルダはそのまま使えます。

assets/
- monstera.png
- kentia.png
- ficus.png
- pothos.png

## GitHub

このZIP内の index.html で既存の index.html を上書きしてください。
assets フォルダは変更不要です。
