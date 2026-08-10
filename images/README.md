# サムネイル画像置き場

`index.html` の各ツールカードが以下のファイル名を参照しています。
ここに同名で置くと自動で表示されます（ファイルが無い場合はサムネ枠ごと非表示になり、これまで通りのレイアウトになります）。

| ファイル名 | ツール |
| --- | --- |
| `uchinoko_act.png` | うちの子ゲームになっちゃいました |
| `talk_card.png` | Talk Card Generator -TCG- |
| `mosaicn.png` | 簡易モザイクツール -モザイくん with STP- |
| `pring_alamode.png` | 流体シミュレーター Pudding a la mode |
| `gion_maker.png` | 擬音メーカーExtra |
| `chichi2x.png` | ちちぷい→X投稿ツール |
| `alka.png` | 常駐型詠唱補助機関・Alka 〜おるか〜 |
| `honlog.png` | ホンログ |

## 推奨サイズ

- 表示サイズは幅 250px・アスペクト比 16:10（= 250×156）
- Retina 対応のため **500×312** 以上で書き出すのがおすすめ（例: 1000×625 でも可）
- `object-fit: cover` + `object-position: top center` で切り抜かれるので、
  画面上部（タイトルバーやメインUI）が写っていれば比率がずれても破綻しません
- `.png` 以外を使いたい場合は `index.html` 側の `src` を書き換えてください
