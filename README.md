# dougakun

GitHub Pages で動画を表示するだけのシンプルなサイトです。

## 使い方

1. `videos` フォルダに表示したい動画ファイル (mp4 推奨) を置く
2. [index.html](index.html) 内の `videos/sample.mp4` を実際のファイル名に書き換える
3. GitHub にリポジトリを push する
4. リポジトリの **Settings > Pages** で公開ブランチ (例: `main`) を設定する
5. 数分後、`https://<ユーザー名>.github.io/<リポジトリ名>/` で公開される

## YouTube などの動画を埋め込みたい場合

`index.html` の `<video>` タグを YouTube の `<iframe>` 埋め込みコードに差し替えてください。
