# parcel-box-key-checker

宅配ボックスの番号が不在票に記載された番号と違ったすべての人に送る

## これは何？

宅配ボックスの番号が、配送業者から指定された番号で開かなかったときに利用します。
通知された4桁の数字を入力することで「間違えやすそうな4桁の候補」を表示します。

表示される候補はルールベースで作成しており、現在は、以下の定義に準拠します。

1. 4桁を並べ替えてできる4桁 (1234 -> 1243)
1. 4桁のうち1桁が上下にズレている (1234 -> 1244)
1. 4桁すべてが上にズレる、または下にズレる (1234 -> 2345)
1. 1と2の組み合わせパターン (1234 -> 5213) 

## なんでペライチHTMLなの？

- とりあえず機能が欲しかった
  - Copilotくんに9割頑張ってもらった
- 枯らしたかった
  - この内容で、依存ライブラリの変更に追従するモチベがあまりない
