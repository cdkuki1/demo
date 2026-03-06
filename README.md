# サロン・ルミエール - 擬似サイト

参考サイト（aroma-fantasy.com）の構成を模した、高級アロマリラクゼーションサロンのデモサイトです。

## 構成

- **index.html** - メインのHTML
- **styles.css** - スタイルシート
- **script.js** - モバイルメニューなどの軽いインタラクション

## セクション

- ヘッダー（固定ナビゲーション）
- ヒーロー
- クイックリンク
- PICK UP（ピックアップセラピスト）
- EVENT（開催中イベント）
- NEW THERAPIST（新人セラピスト）
- RANKING（ランキング）
- INFORMATION（最新情報）
- SCHEDULE（本日の出勤）
- フッター

## 表示方法

ブラウザで `index.html` を直接開くか、ローカルサーバーで起動してください。

```bash
# Python 3
python -m http.server 8000

# または npx
npx serve .
```

その後、http://localhost:8000 にアクセスしてください。
