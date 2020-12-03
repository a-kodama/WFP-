# 🌳 [WFP] β テスト運営レポート



このページは、6月2日（火）より実施が始まった Whiteboard Free Project（通称 WFP ）の β テストについて、そこであがった **不具合や要望と、その対応状況を可視化** するためのページです。



## 対応サイクルについて

β テスト期間中は次の週次サイクルで不具合の改修、要望の対応を行います。

### 水曜日

前週集計よりあとに β テスト実施アンケート（ Google フォーム）に寄せられた不具合・要望を集計します。

### 木曜日

β テスト運営レポート（つまりこのページ）を更新します。

更新内容は水曜日に集計された不具合・要望の一覧化と、各タスクの対応状況の更新です。



## 不具合・要望一覧

### Milestone

> WFP ではプロジェクト立ち上げのタイミングで現在実装されていないいくつかの機能を提供する予定でした。
>
> β テストでは体験することができませんが、今後実装が予定されている機能を紹介します。
>
> （要望とかぶりが多いので、予めこちらを確認してからフィードバックしてもらえると泣いて喜びます）

- **座席予約機能**
- **バタコさん機能**（ゴミ当番お知らせ）
- **パートナーさん利用のための準備**（姓名登録など）

### Open

| No    | 概要                                                         | カテゴリー                              | 対応状況 |
| ----- | ------------------------------------------------------------ | --------------------------------------- | -------- |
| 3    | [着席の履歴を見たい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-3.md)                                           | <span style="color: blue;">要望</span>  |   未定       |
| 21 | 他の人の着席・退席をできるようにほしい（ PM 休の退席忘れ対策）   | <span style="color: blue;">要望</span>  |          |
| 25-1 | 着席・退席のアラートはトーストのほうが好ましい | <span style="color: blue;">要望</span> |          |
| 27 | レイアウトが分かりづらいので、机の枠線を表示してほしい | <span style="color: blue;">要望</span> |          |
| 30 | ブラウザ幅が狭い場合にヘッダーのボタンが機能しない | <span style="color: red;">不具合</span> |          |
| 33 | カレンダー表示中に退席されるとカレンダーが真っ白になってしまう | <span style="color: red;">不具合</span> |          |
| 35 | TeamSpirit と連動してほしい | <span style="color: blue;">要望</span> |          |
| 38   | 通知の未読が0件なのに、バッジが「1」となっている             | <span style="color: red;">不具合</span> |          |
| 40   | 休みの情報とか時差出勤の情報が必要かも…                      | <span style="color: blue;">要望</span>  |          |
| 42   | PSC Slackに「WFP本日の着席状況！」とかを通知してくれるBotを作ると面白そう | <span style="color: blue;">要望</span>  |          |

### Close

| No   | 概要                                                         | カテゴリー                              | 対応状況 |
| ---- | ------------------------------------------------------------ | --------------------------------------- | -------- |
| 1    | [電話をマウスオーバーすると、内線番号より上に電話マークが重なって見にくいものがある](https://github.com/a-kodama/WFP_beta_test/blob/master/Beata-1.md) | <span style="color: red;">不具合</span> | 完了     |
| 2    | [検索によって座席表の下のフッタが上にあがったきて、座席と被ってしまう（レイアウト崩れ）](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-2.md) | <span style="color: red;">不具合</span> | 完了     |
| 4    | [出社予定を登録したい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-4.md) | <span style="color: blue;">要望</span>  | 対応なし |
| 5    | [チュートリアルを初回だけではなく、何度も見たい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-5.md) | <span style="color: blue;">要望</span>  | 完了     |
| 6    | [自分が着席する前でも他の人のカレンダーを見たい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-6.md) | <span style="color: blue;">要望</span>  | 完了     |
| 7    | [カレンダーの表示を大きくしてほしい（表示サイズを変更できるようにしてほしい）](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-7.md) | <span style="color: blue;">要望</span>  | 完了     |
| 8    | [検索の際、表示中の部屋に在席してない旨（もしくは別の部屋に在席している旨）を通知して欲しい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-8.md) | <span style="color: blue;">要望</span>  | 完了     |
| 9    | [在宅の人の所属がわかるようにしてほしい（「所属」を切り替えても何も変わらない）](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-9.md) | <span style="color: blue;">要望</span>  | 完了 |
| 10   | [アイコンや下の名前だと、ぱっと見誰なのかわかりづらいので、苗字にして欲しい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-10.md) | <span style="color: blue;">要望</span>  | 対応なし |
| 11   | [表示される名前を苗字にしてほしい（ [β - 10] と同様）](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-11.md) | <span style="color: blue;">要望</span>  | 対応なし |
| 12   | [ソーシャルディスタンス確保のために空けている箇所は席を非アクティブにするなどしてほしい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-12.md) | <span style="color: blue;">要望</span>  | 完了     |
| 13   | [会議室や休憩スペース（打合せスペース）の利用状況や予約ができるようにしてほしい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-13.md) | <span style="color: blue;">要望</span>  | 対応なし |
| 14   | [退席せずに帰宅した場合、日付が変わるとリセットされるのでしょうか？](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-14.md) | <span style="color: green;">質問</span> | 完了     |
| 15-1 | [座席予約機能と日付選択項目を追加してほしい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-15-1.md) | <span style="color: blue;">要望</span>  | マイルストーン |
| 15-2 | [電話の取次ぎをする人が困らないように、出社予定時刻が分かる仕組みがほしい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-15-2.md) | <span style="color: blue;">要望</span>  | 対応なし |
| 15-3 | [ゴミ当番が分かる仕組みが欲しい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-15-3.md) | <span style="color: blue;">要望</span>  | マイルストーン |
| 15-4 | [大阪、東京の部屋も対応してほしい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-15-4.md) | <span style="color: blue;">要望</span>  | 完了 |
| 15-5 | [会議室にも対応してほしい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-15-5.md) | <span style="color: blue;">要望</span>  | 対応なし |
| 16   | [部屋の向きが分かりくいので、何か目印を入れてほしい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-16.md) | <span style="color: blue;">要望</span>  | 完了     |
| 17   | [各部屋に何人座っているのか数字を表示してほしい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-17.md) | <span style="color: blue;">要望</span>  | 完了     |
| 18 | [着席済の人をクリックすると、真っ白なダイアログが表示される](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-18.md) | <span style="color: red;">不具合</span> | 完了 |
| 19 | [役員をターゲットに検索できない](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-19.md) | <span style="color: red;">不具合</span> |          |
| 20   | [総務が「きく」に移動したため部屋を増やしてほしい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-20.md) | <span style="color: blue;">要望</span>  | 完了     |
| 22   | [検索は部屋をまたいだ検索という仕様なのでしょうか？](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-22.md) | <span style="color: green;">質問</span> | 完了     |
| 23 | [「くすのき」のドアの場所が違うので変えてほしい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-23.md) | <span style="color: blue;">要望</span>  | 完了 |
| 24   | [検索結果で透過状態のアイコンをクリックするとカレンダーが正しく表示されない](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-24.md) | <span style="color: red;">不具合</span> | 完了     |
| 25-2 | [他の席に着席する際に、一度退席しなくてもできるようにしてほしい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-25_2.md) | <span style="color: blue;">要望</span> | 完了 |
| 26 | [席の予約ができるようにしてほしい（[ β - 15-1] と同様）](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-26.md) | <span style="color: blue;">要望</span> | マイルストーン |
| 28 | [倉敷以外の事務所も対応してほしい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-28.md) | <span style="color: blue;">要望</span> | 完了 |
| 29 | [在宅Roomに何度でも座れてしまう](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-29.md) | <span style="color: red;">不具合</span> | 完了 |
| 31 | [在宅Roomに何度でも座れてしまう（[β - 29] と同様）](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-29.md) | <span style="color: red;">不具合</span> | 完了 |
| 32 | [「くすのき」をレイアウト変更したので座席のは位置を変更してほしい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-32.md) | <span style="color: blue;">要望</span> | 完了 |
| 34 | [「けやき」をレイアウト変更したので対応してほしい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-34.md) | <span style="color: blue;">要望</span> | 完了 |
| 36   | [きくの収容人数の変更が必要かも](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-36.md)                               | <span style="color: blue;">要望</span>  | 完了           |
| 37   | [部署名の変更が必要かも](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-37.md)                                       | <span style="color: blue;">要望</span>  | 完了           |
| 39   | [大阪オフィスも追加してほしい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-39.md)                                 | <span style="color: blue;">要望</span>  | 完了           |
| 41   | [部屋ごと（or島ごと）の電話番号・内線番号を表示してほしい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-41.md)     | <span style="color: blue;">要望</span>  | 完了           |