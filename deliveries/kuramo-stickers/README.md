# クラモ君 LINEスタンプ40種類・納品

追加のお手本4枚を基準に制作したNo.01〜40の最新版です。

## LINE申請用ZIP

**LINEへアップロードする場合は、[LINE-submit-40-stickers.zipをダウンロード](LINE-submit-40-stickers.zip?raw=true)してください。**

ZIPの直下に次の42枚だけを収録しています。すべてPNG（8bit RGBA）・背景透過済みで、実ファイルを検査しました。

| 内容 | ファイル名 | サイズ |
|---|---|---|
| スタンプ40枚 | 01.png〜40.png | 各370×320px |
| メイン画像 | main.png | 240×240px |
| タブ画像 | tab.png | 96×74px |

容量は約5.6MBです。一覧画像、編集用の高解像度画像、レポート類は申請ZIPに含めていません。

メインを個別に取得する場合は [main.png](main.png?raw=true)、タブは [tab.png](tab.png?raw=true) を使用できます。[全42画像の仕様検査結果](line-submission-checks.json)も保存しています。LINE側でのアップロード受理や審査通過は、こちらでは実行していません。

## Canvaで調整する場合

[Canva用・高解像度PNG40枚をダウンロード](canva-editing-40.zip?raw=true)

ZIPを解凍すると、01.png〜40.pngの個別画像が入っています。1480×1280px、RGBA、背景透過済みの編集素材です。Canvaで調整後はスタンプを最大370×320px、メインを240×240px、PNG・背景透過で書き出してください。

一覧画像の左上にあった確認用の「No.〇〇」は、すべて削除しました。個別PNGにも確認用番号は表示されません。下の一覧は確認用です。Canvaで使う際は一覧から切り出さず、上記の個別PNGをご利用ください。

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
| **[LINE申請用ZIP](LINE-submit-40-stickers.zip?raw=true)** | **スタンプ40枚370×320px・main240×240px・tab96×74px。全42枚透過PNGのみ** | **約5.6MB** |
| [Canva調整用・高解像度PNG40枚](canva-editing-40.zip?raw=true) | 番号表示なし・背景透過・1480×1280pxの個別PNG40枚 | 約38MB |
| [PNG40枚・品質レポート](kuramo-40-stickers.zip?raw=true) | 個別PNG40枚、一覧、制作管理表、品質評価、仕様検査 | 約10MB |
| [編集用元データ](kuramo-production-sources.zip?raw=true) | 原寸イラスト・マスター・編集用SVG・フォントとライセンス・プロンプト・スクリプト・修正前画像 | 約101MB |
| [一覧画像の原寸表示](all-40.png?raw=true) | 5列×8行、全40種類 | 約4.5MB |

## 全40種類の一覧（番号表示なし）

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
467908fcff37af997ef8a5ca1ef5dce0039ca451ea06dbe7449b927248daac57  LINE-submit-40-stickers.zip
92881bda5720dd8e6a2835d5ecebb77f27e475fb0df1ecb8651d197d2c68319f  main.png
4d207218a7cf7937ba9630c204d90703393c120bdeaab5d22224bc148d75544d  tab.png
3bf2332fa6673cd29fec2b2dd4ff9bc82984c4edffaf1d294e0f4b2858660673  line-submission-checks.json
32e36f898331ac5a47e7b1bdd1ff1ed62e7733050652db08c7506864c9af41ae  canva-editing-40.zip
d01e8f4fc6184ff4b247ab5369024920603a817f8fdd95516e5368d46f76d4e1  kuramo-40-stickers.zip
8c5c8a5ffe60bbccbd2c2f435e54400a1338ac347b7f55392a73c2e8c58c8794  kuramo-production-sources.zip
467908fcff37af997ef8a5ca1ef5dce0039ca451ea06dbe7449b927248daac57  line-upload-candidate.zip
6ad17e45a9b3229aec539a426a1fa176a7cb7837a47cc7f96873900186b4608c  all-40.png
8e1b32c19023fcec58b88d9bdcaf978ddff5e33b202364c0d3f79842d3d01dbe  No18.png
c1f48a8a7ccfdc72dd32fe2c29754996b62d49dd00cd409c5c27246a08c4ce37  No22.png
ada4f2f152162ed692f847785490c7f5a9b2cffa3381d81cdaa9c76ae5c96992  No36.png
09c7ec226609fd8617e581502f9687970eec8ec25efcfdb01f71201c2de2f23a  No39.png
5cab57e11772cac7ee225846ef0894ca326caff64d5617a94f35594e9dd1c17a  revised-18-22-36-39.png
```
