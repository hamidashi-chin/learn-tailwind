# Tailwindcss完全入門　v3.0

## 初期セットアップ
[公式サイト](https://tailwindcss.com/)

### インストール

公式サイトのGetting Startedに書いてある。
たぶんバージョンによってインストール方法変わっていきそうなのでここにはインストール方法は書かない。

### ビルドを簡単に行えるようにする

```bash
npm init -y
npm run build
```

### tailwindcssのinput.cssに記載するインポート部分の波線消す
VSCodeのsetting.jsonの一番下に書きを追記する
```json
"css.lint.unknownAtRules": "ignore"
```