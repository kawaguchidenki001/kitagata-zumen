# 北方住宅 図面ビューア

県営北方住宅 室内照明LED化改修工事 の図面ビューア（静的サイト）。

- 棟 → 階 → 号室 の3段階で図面を表示
- 号室ごとの改修器具リスト（記号・型番・写真）／器具種類（写真区分）
- 取替済み器具のマーク、器具カードクリックで図面上シンボルを点滅

## 公開方法（GitHub Pages）
1. このリポジトリの内容（`index.html` / `images/` / `photos/` / `.nojekyll`）をそのまま配置
2. Settings → Pages → Source を「Deploy from a branch」、Branch を `main` / `(root)` に設定
3. `https://<ユーザー名>.github.io/<リポジトリ名>/` で公開

ビルド不要。ファイルを差し替えてpushするだけで更新されます。
