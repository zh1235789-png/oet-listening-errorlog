# OET Listening エラーログ

OET Listening（Part A）の精度を上げるための、落とした語を記録する iPhone 向け PWA（単一HTML・バニラJS・外部ライブラリなし）。

公開URL（GitHub Pages）: https://zh1235789-png.github.io/oet-listening-errorlog/

## 機能
- エラーの追加 / 編集 / スワイプ削除（区分5種: 🔤綴り・🔁文法形・👂音・⚡速さ・🧠言い換え）
- 区分・日付・フリーワードでの絞り込み（新しい順）
- 区分別の件数グラフ（今週 / 全期間）
- 🔥重点ウォッチ自動昇格（同じ語が2回以上）
- 週次サマリー（日曜起点）＋次週の重点提示
- Obsidian エラーログとの Markdown 相互コピペ（import / export）
- JSON バックアップ / 復元
- localStorage 永続化（キー: `oet-listening-errorlog-v1`）

## 使い方
Safari で公開URLを開く → 共有 → 「ホーム画面に追加」で全画面アプリ化。データは端末ごとに localStorage 保存。Obsidian 側との同期は「同期」タブの Markdown コピペで行う。
