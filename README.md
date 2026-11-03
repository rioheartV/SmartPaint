# 🎨 SmartPaint

**日本語** | [English](#english)

スマホ・タブレットを PC の液タブにする、無料のペイントアプリです（Windows 10 / 11）。

- 配布ページ: https://rioheartv.github.io/apps/smartpaint/
- ダウンロード: [Releases](../../releases/latest) から `SmartPaint_<版>.zip`（Python などを入れる必要はありません）

## できること

- 同じ Wi-Fi のスマホ・タブレットから描ける（QR コードを読むだけ・何台でも同時に同じ絵を描けます）
- 筆圧・ペンの傾き・入り抜き・払い・手ブレ補正・後補正
- ブラシ 40 種以上・ウォッシュ・混色・紙の目
- レイヤー・フォルダ・クリッピング・マスク・調整レイヤー・ベクターレイヤー・テキスト
- 選択・変形・塗りつぶし（隙間閉じ）・グラデーション・定規・パース定規・対称
- PSD の読み込みと保存・PNG / JPG 書き出し・5 分ごとの自動保存と、落ちた時の復元
- キー・マウスのボタン・ペンのサイドボタン・ホイールの割り当てを自由に変えられます

## はじめかた

1. zip を右クリック →「すべて展開」で、好きな場所に展開します（zip の中から直接起動しないでください）。
2. 展開したフォルダの `SmartPaint.exe` をダブルクリックします。
3. スマホから描く時は、画面上の 📂 を押して出る QR コードを、同じ Wi-Fi のスマホで読み取ります。

「Windows によって PC が保護されました」と出た時は「詳細情報」→「実行」を押してください（作者の電子署名が無いため、初回だけ出ます）。
ファイルが本物か確かめる時は、Releases に書いた SHA256 と `Get-FileHash .\SmartPaint_<版>.zip -Algorithm SHA256` の結果を比べてください。

## 利用規約

ダウンロード・使用の前に、[配布ページの利用規約](https://rioheartv.github.io/apps/smartpaint/#terms)（zip の中の `利用規約.txt` と同じ内容）を読んでください。自己責任で使ってください。
このリポジトリは配布用です。ソースコードは置いていません。

---

<a id="english"></a>

## English

A free painting app that turns your smartphone or tablet into a pen display for your PC (Windows 10 / 11).

- Download page: https://rioheartv.github.io/apps/smartpaint/ (Japanese)
- Download: `SmartPaint_<version>.zip` from [Releases](../../releases/latest) (no Python or other setup required)

### Features

- Draw from phones and tablets on the same Wi-Fi (just scan a QR code; any number of devices can draw on the same canvas at once)
- Pen pressure, tilt, taper in/out, flicks, stabilizer and post-correction
- 40+ brushes, wash (lines that don't darken when overlapped), color mixing, paper texture
- Layers, folders, clipping, masks, adjustment layers, vector layers, text
- Selection, transform, fill (gap closing), gradients, rulers, perspective rulers, symmetry
- PSD import/export, PNG / JPG export, autosave every 5 minutes with crash recovery
- Freely remappable keys, mouse buttons, pen side buttons and wheel

### Getting started

1. Right-click the zip → "Extract All" to any folder (do not run it from inside the zip).
2. Double-click `SmartPaint.exe` in the extracted folder.
3. To draw from a phone, press 📂 and scan the QR code with a phone on the same Wi-Fi.

If "Windows protected your PC" appears, click "More info" → "Run anyway" (shown only on first launch because the app is not code-signed).
To verify the download, compare the SHA256 in the release notes with `Get-FileHash .\SmartPaint_<version>.zip -Algorithm SHA256`.

### Terms of use

Please read the [terms of use](https://rioheartv.github.io/apps/smartpaint/#terms) (Japanese; same as `利用規約.txt` in the zip) before downloading or using. Use at your own risk.
This repository is for distribution only; the source code is not included.
