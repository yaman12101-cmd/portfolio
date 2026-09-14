# Portfolio

生成AI・Excel / VBA・業務自動化まわりで作ったものをまとめたポートフォリオサイトです。

## 構成

```
portfolio/
├─ index.html          … サイト本体（HTML / CSS / JS を1ファイルにまとめています）
└─ assets/
   ├─ image/           … 人物アイコン、資料スライド
   └─ video/           … 実演動画（mp4 / webm）とポスター画像（jpg）
```

ビルドは不要です。`index.html` をブラウザで開けばそのまま動きます。

## 公開について

GitHub Pages で公開する場合は、リポジトリの Settings → Pages で
Branch を `main` / フォルダを `/ (root)` に設定してください。

## 動画について

動画は mp4（H.264）を第一候補、webm（VP9）を予備として読み込みます。
どちらもタップされるまで読み込まれないため、初期表示ではポスター画像だけが表示されます。

差し替える場合は、`index.html` 内の `WORKS` の `video` / `shot` を書き換えてください。
