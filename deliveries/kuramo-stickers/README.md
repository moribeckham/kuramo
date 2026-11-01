# クラモ君 LINEスタンプ40種類・納品

追加のお手本4枚を基準に制作したNo.01〜40の最新版です。

## 最新修正（2026-11-02）

- No.18：チェックリストを両手で相手に差し出すポーズへ修正。
- No.22：開いた手帳を両手で相手に見せるポーズへ修正。ペンは外縁に留めています。
- No.36：メイン文字を「それAIで即解決です」に変更。
- No.39：メイン文字を「定時前にかぎって」に変更。

一覧・PNG一式・LINE申請候補・編集用元データに反映済みです。

[No.18](No18.png?raw=true) / [No.22](No22.png?raw=true) / [No.36](No36.png?raw=true) / [No.39](No39.png?raw=true)

![修正版 No18・22・36・39](revised-18-22-36-39.png)

## ダウンロード

GitHubにログインした状態で、次のリンクから取得してください。ファイル画面が開いた場合は右上のダウンロードボタンを使用できます。

| ファイル | 内容 | 容量 |
|---|---|---:|
| [PNG40枚・品質レポート](kuramo-40-stickers.zip?raw=true) | 個別PNG40枚、一覧、制作管理表、品質評価、仕様検査 | 約10MB |
| [編集用元データ](kuramo-production-sources.zip?raw=true) | 原寸イラスト・マスター・編集用SVG・フォントとライセンス・プロンプト・スクリプト・修正前画像 | 約101MB |
| [LINE申請候補](line-upload-candidate.zip?raw=true) | 01.png〜40.png、main.png、tab.pngをZIPのルートに配置 | 約5.6MB |
| [一覧画像の原寸表示](all-40.png?raw=true) | 5列×8行、全40種類 | 約4.5MB |

## 全40種類の一覧

![クラモ君 LINEスタンプ40種類](all-40.png)

## 検査結果と注意点

- 個別画像40枚、未完成0枚。370×320pxの透過RGBA PNG。
- 最新の指定メイン文字・サブ文字、形式、容量、透過、外周余白の検査：40/40通過。
- 今回の4枚以外の36枚は、直前の納品データとPNGの内容が一致することを確認。
- 制作者の目視評価：92〜95点。各画像の詳細な所見はPNG一式ZIPのquality-report.csv。
- No.39サブは「（まじかよ…）」、No.40は残量1%を確認。
- LINE公式の最新制作ガイドはHTTP 403で取得できなかったため、申請前の最新要件確認が必要です。LINEへの販売申請・公開は行っていません。

## ファイル整合性

SHA-256は以下のとおりです。

```
0a05684249a71f1e548042c89b8495bdb50d5eefb5a7b0943f8ee031a2479c82  kuramo-40-stickers.zip
cbca6ee624251999710d75e05788c97c3fb777cb697275aac03d19fdc8054776  kuramo-production-sources.zip
850d7d6005f6ca7d60469acfa3d6a99753e28bd4ff471a6da1dbf2ce13a4ad6b  line-upload-candidate.zip
91af885ac73ec8865e30fa41c65d3e9d8f1a4562c699c59b8666b16580d3c7b1  all-40.png
8e1b32c19023fcec58b88d9bdcaf978ddff5e33b202364c0d3f79842d3d01dbe  No18.png
c1f48a8a7ccfdc72dd32fe2c29754996b62d49dd00cd409c5c27246a08c4ce37  No22.png
ada4f2f152162ed692f847785490c7f5a9b2cffa3381d81cdaa9c76ae5c96992  No36.png
09c7ec226609fd8617e581502f9687970eec8ec25efcfdb01f71201c2de2f23a  No39.png
ca1f57e8b5612721e6cb89c838db67e0860c542927dd6b1c40a42e9181528747  revised-18-22-36-39.png
```
