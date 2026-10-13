# Randomizer Collection

このリポジトリには、ブラウザですぐに動くルーレットのサンプルをまとめています。

## 使い方

- `index.html` を開いて、使いたいテンプレートを選ぶ
- 各 HTML は CSS と JavaScript が埋め込まれていて、そのまま単独で動く
- 事前に当たりを指定できるようにしてある
- `roulette-easter-egg.html` はイースターエッグ風の割れ演出付き

## ファイル一覧

- `index.html` : テンプレート一覧
- `roulette-simple.html` : シンプルなルーレット
- `roulette-preset.html` : 当たりを事前設定できるルーレット
- `roulette-easter-egg.html` : イースターエッグ割りルーレット
- `roulette-emoji.html` : アイコン中心のルーレット

## 例

ローカルで開く場合:

```bash
python3 -m http.server 8000
```

その後、ブラウザで `http://localhost:8000/` を開くと一覧画面が表示されます。
