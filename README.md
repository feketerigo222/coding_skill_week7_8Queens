# coding_skill_week7_8Queens

## 課題用コード説明

- HTML 上の各マスに行・列・対角のクラスを設定
- クリックしたマスの class を判定。locked があれば何も起きず。
- クリックしたマスに clicked の class を付与、テキストを「Q」に変更。クリックしたマスと同じクラスのテーブルに locked の class を付与、クリック不可にし背景色を変更。クリック回数(clickCnt)を 1 つ増やす。
- クリック回数が 8 回になった時アラートとファンファーレで祝福。

### 問題点・課題点

- クイーンを置いたマスをもう一度クリックするとやり直せる機能を実装しようとしたが、重複部分の処理が面倒だったので断念。クリックした逆順にクイーンを取り除くことは出来た（コメントアウト部分）。
- マスに class を無理矢理設定したために nQueen 問題には対応していない。
