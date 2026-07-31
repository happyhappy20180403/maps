# maps

お客様にお見せする地図の置き場所。`map.jbfudosan.com` で配信している。

## 増やし方

案件ごとにフォルダを1つ作り、その中に `index.html` を置くだけ。

```
tour-20260731/index.html  →  https://map.jbfudosan.com/tour-20260731/
```

push すると1分ほどで反映される。DNSの追加作業は不要。

## 守ること

- **内部メモ（指示書など）は絶対に置かない。** ここに置いたものは URL を知れば誰でも見られる
- ルートの `index.html` は案件を並べない。中身を推測されないための無地のページにしてある
- 各ページに `<meta name="robots" content="noindex, nofollow, noarchive">` を入れる
