# 動くお絵かきAR

紙に描いた絵の画像をアップロードすると、Hiroマーカー上で絵が動くWeb ARアプリです。  
静的ファイルだけで動くので GitHub Pages にそのまま置けます。

## 使い方

1. `index.html` をGitHubリポジトリにアップロード
2. GitHubの `Settings` → `Pages`
3. `Deploy from a branch` を選び、`main` / `/root` を公開元にする
4. 表示されたURLをスマホで開く
5. `hiro-marker-print.html` を開いてHiroマーカーを印刷
6. アプリで自分の絵の画像を選んで、カメラをマーカーに向ける

## 注意

- カメラ利用のため、GitHub PagesなどのHTTPS環境で開いてください。
- iPhone Safariは通常のWebXR ARに対応していないため、マーカーAR方式にしています。
- 自分の絵の背景を透明PNGにすると、より自然に見えます。


## 印刷用Hiroマーカー

`hiro-marker-print.html` をブラウザで開き、A4用紙に印刷してください。
印刷時は「ページに合わせる」または倍率100%を推奨します。
マーカーは折り曲げず、明るい場所でカメラに映してください。

## ファイル構成

- `index.html` — ARアプリ本体
- `hiro-marker-print.html` — 印刷用Hiroマーカー
- `README.md` — 使い方
