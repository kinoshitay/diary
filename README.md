# diary

日々の出来事、作業、気づき、次にやることをMarkdownで記録するためのリポジトリです。

## ディレクトリ構成

```text
diary/
  YYYY/
    MM/
      DD.md
  templates/
    daily.md
```

- `diary/YYYY/MM/DD.md`: 日付ごとの日記
- `diary/templates/daily.md`: 新しい日記を作るためのテンプレート

## 日記の追加方法

1. `diary/templates/daily.md` を対象日の日付へコピーします。
2. ファイル名と先頭見出しを `YYYY-MM-DD` に変更します。
3. 「今日の一言」「やったこと」「気づき・学び」「明日やること」を記入します。

例:

```text
diary/2026/05/04.md
```

## 公開時の注意

このリポジトリへ記録する内容はGitHubで公開される可能性があります。個人情報、認証情報、private URL、顧客情報、社外秘の内容は書かないでください。
