# ①課題番号-プロダクト名

家計簿webアプリ

## ②課題内容（どんな作品か）

- phpMyadminを使って、収支を投入できる
- 投入した収支を一覧で確認できる

## ③DEMO

https://ebitaku.sakura.ne.jp/kakeiboapp/index.php

## ④作ったアプリケーション用のIDまたはPasswordがある場合

なし

## ⑤工夫した点・こだわった点

- これまでの課題よりも実用的にするために、きれいなUIを心掛けた
- 収支一覧表の、収入と支出を一目見てわかるように色を付けた

## ⑥難しかった点・次回トライしたいこと(又は機能)

- DBは作成済みなので、カテゴリや財布の選択肢を自分で追加できるようにしたい
- 絞り込み機能を実装するにあたり、select文を入れてみたが、以下のエラーが出てしまい、取得したいカラムがundefinedとなってしまった。
  - :Undefined array key "syushi" in C:\xampp\htdocs\kakeibo\kakeiboapp\insert.php on line 6
- 各レコードに編集ボタンを設置して、投入後の編集を可能にしたい（SQLのupdate,delete?)
- 別ページに収支のグラフを挿入したい（chartjsのリベンジ）

## ⑦質問・疑問・感想、シェアしたいこと等なんでも

- [質問]
- [感想]
- Chartjsを使うことができなかったので、違う方法でのグラフ表示を検討したい。
- [参考記事]
  - 1.参考にした家計簿アプリ [https://tameru.me/]
# kakeiboapp
