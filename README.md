```c0.xslx```
=============


-----
## Tasksタブ
課題とその詳細を入力してリスト化し機械判読可能にします。
識別用のコードを割り振っておくことで、Mainタブで予定を組む際にコードを入力するだけで情報を自動補完できるようになります。

![c0_screenshot_1](https://user-images.githubusercontent.com/42954293/106844906-19bc8680-66ed-11eb-9d79-e658b5c2ed5b.png)
**列の概要**
| 列 | 概要 |
|:-----------:|:------------|
| ```A``` | 科目名 [文字列] |
|```B``` | 問題集・参考書名 [文字列] |
|```C``` | チェックボックス [✓] |
|```D``` | 周（同じ課題に繰り返して取り組む場合、何回目か記入） [数字] |
| ```E``` | ID（ハッシュ値）各課題に固有の識別用コードを与える [半角英数字文字列] |
| ```F``` | 課題名 [文字列] |
| ```G``` | 各課題の一問（ページなども可）あたりの所要時間 [数字] |
| ```H,I``` | 問（またはページなど）の範囲 [数字,数字] |
| ```J``` | 量、問題（ページ）数 [自動表示] |
| ```K``` | 合計所要時間（分） [自動表示] |
| ```L``` | 合計所要時間（時間） [自動表示] |
| ```M```より左 | 機械使用欄 [自動表示] |

各項目の入力方法は画像の例を参考にしてください。
```J```列から右側には何も入力しないでください。

-----
## Mainタブ
行方向（縦向き）の時間軸に沿った予定作成ページです。

![c0_screenshot_2](https://user-images.githubusercontent.com/42954293/106845237-e0d0e180-66ed-11eb-8e7d-4cc8130415b2.png)

画像中の```F```列,```L```列,```R```列にTasksタブで割り振ったコードを入力し、つづいて、その右側の"範囲"列にその日取り組む予定の問題番号やページ数などの始めと終わりの数字を入力します。それ以外の欄では"備考"欄（備考は必要に応じて自由に使ってください）以外何も入力しないでください。
"計"の列にそれぞれの日の合計勉強時間が時間単位で表示されます。
