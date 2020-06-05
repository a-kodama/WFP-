# 🌳 [WFP] β テスト運営レポート



このページは、6月2日（火）より実施が始まった Whiteboard Free Project（通称 WFP ）の β テストについて、そこであがった **不具合や要望と、その対応状況を可視化** するためのページです。



## 対応サイクルについて

β テスト期間中は次の週次サイクルで不具合の改修、要望の対応を行います。

### 水曜日

前週集計よりあとに β テスト実施アンケート（ Google フォーム）に寄せられた不具合・要望を集計します。

### 木曜日

β テスト運営レポート（つまりこのページ）を更新します。

更新内容は水曜日に集計された不具合・要望の一覧化と、各タスクの対応状況の更新です。



## WFP で今後実装される予定の機能

WFP ではプロジェクト立ち上げのタイミングで現在実装されていないいくつかの機能を提供する予定でした。

β テストでは体験することができませんが、今後実装が予定されている機能を紹介します。

（要望とかぶりが多いので、予めこちらを確認してからフィードバックしてもらえると泣いて喜びます）

- 座席予約機能
- バタコさん機能（ゴミ当番お知らせ）
- パートナーさん利用のための準備（姓名登録など）



## 不具合・要望一覧

| No    | 概要                                                         | カテゴリー                              | 対応状況 |
| ----- | ------------------------------------------------------------ | --------------------------------------- | -------- |
| 1    | [電話をマウスオーバーすると、内線番号より上に電話マークが重なって見にくいものがある](https://github.com/a-kodama/WFP_beta_test/blob/master/Beata-1.md) | <span style="color: red;">不具合</span> | 完了     |
| 2    | [検索によって座席表の下のフッタが上にあがったきて、座席と被ってしまう（レイアウト崩れ）](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-2.md) | <span style="color: red;">不具合</span> | 完了     |
| 3    | [着席の履歴を見たい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-3.md)                                           | <span style="color: blue;">要望</span>  |   未定       |
| 4    | [出社予定を登録したい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-4.md)                                         | <span style="color: blue;">要望</span>  |   対応なし       |
| 5    | [チュートリアルを初回だけではなく、何度も見たい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-5.md)               | <span style="color: blue;">要望</span>  | 完了         |
| 6    | [自分が着席する前でも他の人のカレンダーを見たい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-6.md) | <span style="color: blue;">要望</span>  | 対応予定 |
| 7    | [カレンダーの表示を大きくしてほしい（表示サイズを変更できるようにしてほしい）](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-7.md) | <span style="color: blue;">要望</span>  | 対応予定 |
| 8    | [検索の際、表示中の部屋に在席してない旨（もしくは別の部屋に在席している旨）を通知して欲しい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-8.md) | <span style="color: blue;">要望</span>  | 対応中 |
| 9    | 在宅の人の所属がわかるようにしてほしい（「所属」を切り替えても何も変わらない） | <span style="color: blue;">要望</span>  |          |
| 10   | [アイコンや下の名前だと、ぱっと見誰なのかわかりづらいので、苗字にして欲しい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-10.md) | <span style="color: blue;">要望</span>  | 対応なし |
| 11   | [表示される名前を苗字にしてほしい（ [β - 10] と同様）](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-11.md) | <span style="color: blue;">要望</span>  | 対応なし |
| 12   | [ソーシャルディスタンス確保のために空けている箇所は席を非アクティブにするなどしてほしい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-12.md) | <span style="color: blue;">要望</span>  | 完了 |
| 13   | 会議室や休憩スペース（打合せスペース）の利用状況や予約ができるようにしてほしい | <span style="color: blue;">要望</span>  |          |
| 14   | [退席せずに帰宅した場合、日付が変わるとリセットされるのでしょうか？](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-14.md) | <span style="color: green;">質問</span> | 完了 |
| 15-1 | 座席予約機能と日付選択項目を追加してほしい                   | <span style="color: blue;">要望</span>  |          |
| 15-2 | 電話の取次ぎをする人が困らないように、出社予定時刻が分かる仕組みがほしい | <span style="color: blue;">要望</span>  |          |
| 15-3 | ゴミ当番が分かる仕組みが欲しい                               | <span style="color: blue;">要望</span>  |          |
| 15-4 | 大阪、東京の部屋も対応してほしい                             | <span style="color: blue;">要望</span>  |          |
| 15-5 | 会議室にも対応してほしい                                     | <span style="color: blue;">要望</span>  |          |
| 16 | [部屋の向きが分かりくいので、何か目印を入れてほしい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-16.md) | <span style="color: blue;">要望</span>  | 完了 |
| 17 | [各部屋に何人座っているのか数字を表示してほしい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-17.md) | <span style="color: blue;">要望</span>  | 対応中 |
| 18 | 着席済の人をクリックすると、真っ白なダイアログが表示される | <span style="color: red;">不具合</span> |          |
| 19 | 役員をターゲットに検索できない                      | <span style="color: red;">不具合</span> |          |
| 20 | [総務が「きく」に移動したため部屋を増やしてほしい](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-20.md) | <span style="color: blue;">要望</span>  | 対応中 |
| 21 | 他の人の着席・退席をできるようにほしい（ PM 休の退席忘れ対策）   | <span style="color: blue;">要望</span>  |          |
| 22 | [検索は部屋をまたいだ検索という仕様なのでしょうか？](https://github.com/a-kodama/WFP_beta_test/blob/master/Beta-22.md) | <span style="color: green;">質問</span> | 完了 |
| 23 | 「くすのき」のドアの場所が違うので変えてほしい               | <span style="color: blue;">要望</span>  |          |
| 24 | 検索結果で透過状態のアイコンをクリックするとカレンダーが正しく表示されない | <span style="color: red;">不具合</span> |          |

