# JUG SCAN v1.4.0

正式Deploy候補。iPhone 17（402 CSS px想定）での巡回入力を主目的に調整。

## 主な仕様
- 店舗別・日付別にiPhone内（IndexedDB）保存
- 店舗の追加 / 名前変更 / 削除
- 機種選択：ファンキー2 / ネオアイム / ハッピーV3 / マイジャグV / ゴージャグ3 + その他現行機種
- 台番号 / 累計G / BB / RB / 備考
- REG確率 / 合算確率の即時計算
- 同一日・同一店舗・同一台番号の重複時は上書き確認
- 登録済み台の編集 / 削除
- 登録順 / REG順 / 合算順 / 台番号順
- 履歴表示
- 生成画像をHTML内data URIとして埋め込み、GitHub Pages上の画像パス切れを回避
- iPhone Safe Area / VisualViewport / キーボード表示時の下部ナビ退避

## GitHub Pagesへ配置するファイル
- index.html
- sw.js
- manifest.webmanifest
- icons/

`app.source.js` と `styles.source.css` は監査用ソースで、公開には必須ではありません。
