# 更新履歴

## F-RevoCRM7.3.6
### パッチ適用方法
- ファイル、DBのバックアップを確実に取得してください
- 差分ファイルを上書き更新してください
- 以下のURLにアクセスし、マイグレーションを実施してください。  
`https://example.com/frevocrm/index.php?module=Migration&view=Index&mode=step1`


* 機能改善
  - [#503](https://github.com/thinkingreed-inc/F-RevoCRM/issues/503) [要望]リスト作成時の項目選択で関連モジュール名を表示して欲しい
  - [#424](https://github.com/thinkingreed-inc/F-RevoCRM/issues/424) [要望]カスタムフィールドを追加する上限を設定してほしい
  - [#391](https://github.com/thinkingreed-inc/F-RevoCRM/issues/391) [要望]ポータルの初期パスワードが簡単な英数で生成される
  - [#388](https://github.com/thinkingreed-inc/F-RevoCRM/issues/388) [要望]CHANGELOG.mdを作る
  - [#384](https://github.com/thinkingreed-inc/F-RevoCRM/issues/384) [要望]「すべて」というリストが先頭にならないケースが有る
  - [#373](https://github.com/thinkingreed-inc/F-RevoCRM/issues/373) [要望]契約モジュールのテーブルにprimary keyがない
  - [#371](https://github.com/thinkingreed-inc/F-RevoCRM/issues/371) [要望]マイグレーションでINDEXが効いていないuitype10(関連項目)にINDEXを追加したい
  - [#364](https://github.com/thinkingreed-inc/F-RevoCRM/issues/364) [要望]関連項目を追加した際にINDEXを付与して欲しい
  - [#358](https://github.com/thinkingreed-inc/F-RevoCRM/issues/358) [要望]活動を完了で作成した際、親レコードの最終活動日の更新条件を変えてほしい
  - [#328](https://github.com/thinkingreed-inc/F-RevoCRM/issues/328) [要望]コメント削除機能が欲しい
  - [#315](https://github.com/thinkingreed-inc/F-RevoCRM/issues/315) [要望]項目の並び順変更時の挙動を変えたい
  - [#297](https://github.com/thinkingreed-inc/F-RevoCRM/issues/297) [要望] インポートのマッピングで自動生成番号の項目を選択できるようにしてほしい
  - [#289](https://github.com/thinkingreed-inc/F-RevoCRM/issues/289) [要望]ユーザーの管理項目をシステム設定の画面上から変更できるようにしてほしい
* 不具合修正
  - [#518](https://github.com/thinkingreed-inc/F-RevoCRM/issues/518) [不具合]見積印刷時に下部に線が入ってしまう
  - [#515](https://github.com/thinkingreed-inc/F-RevoCRM/issues/515) [質問]WEBフォームから取り込まれた複数選択肢の区切り記号について
  - [#498](https://github.com/thinkingreed-inc/F-RevoCRM/issues/498) [不具合] 登録/変更画面からuitype10の詳細登録を経由すると入力中のデータが消える
  - [#480](https://github.com/thinkingreed-inc/F-RevoCRM/issues/480) [不具合] 同じファイルを選択した際の警告の翻訳漏れ
  - [#474](https://github.com/thinkingreed-inc/F-RevoCRM/issues/474) [不具合]ユーザーをインポートするとカレンダー設定のタイムゾーンがSamoaになる
  - [#472](https://github.com/thinkingreed-inc/F-RevoCRM/issues/472) [不具合]メールアドレス項目が途中で切れて保存される
  - [#469](https://github.com/thinkingreed-inc/F-RevoCRM/issues/469) [不具合]docker composeからセットアップができない
  - [#452](https://github.com/thinkingreed-inc/F-RevoCRM/issues/452) [不具合]F-RevoCRMのワークフロー機能にて送信されるメールにて、TEXT形式部分のマルチバイト文字が欠落している。
  - [#440](https://github.com/thinkingreed-inc/F-RevoCRM/issues/440) [不具合]概要画面で非公開の活動の「詳細内容」が確認できてしまう
  - [#421](https://github.com/thinkingreed-inc/F-RevoCRM/issues/421) [不具合]タグを複数設定し、データ編集するとタグが増えてしまう
  - [#420](https://github.com/thinkingreed-inc/F-RevoCRM/issues/420) [不具合] タグを設定すると、編集内容が反映されない
  - [#414](https://github.com/thinkingreed-inc/F-RevoCRM/issues/414) [不具合]価格表モジュールに関連フィールドを追加するとレポートが表示されない
  - [#411](https://github.com/thinkingreed-inc/F-RevoCRM/issues/411) [不具合]大文字の拡張子となっているCSVファイルをインポートしようとするとExeptionが発生する
  - [#410](https://github.com/thinkingreed-inc/F-RevoCRM/issues/410) [不具合]送信メールサーバーを設定した際に送られるメールの本文が英語になっている
  - [#404](https://github.com/thinkingreed-inc/F-RevoCRM/issues/404) [不具合]サービスモジュールに関連フィールドを追加するとレポートが表示されない
  - [#401](https://github.com/thinkingreed-inc/F-RevoCRM/issues/401) [不具合]活動のインポート時、管理画面から追加した項目があるとインポートに失敗する
  - [#393](https://github.com/thinkingreed-inc/F-RevoCRM/issues/393) [不具合]カスタム項目「選択肢(単数)」のデフォルト値表示がおかしい
  - [#389](https://github.com/thinkingreed-inc/F-RevoCRM/issues/389) [不具合]一覧画面で一部の区切り線が消える
  - [#387](https://github.com/thinkingreed-inc/F-RevoCRM/issues/387) [不具合]カレンダー上から詳細入力を行ったあとの戻り先が遷移元のカレンダーにならない
  - [#385](https://github.com/thinkingreed-inc/F-RevoCRM/issues/385) [不具合]Contactsのportalをonとした際に送られてくるメールがすべて英語。
  - [#370](https://github.com/thinkingreed-inc/F-RevoCRM/issues/370) [不具合]ワークフロー新規作成・保存後の画面遷移で、フィルタが解除されて「全て　ワークフロー」になってしまう
  - [#363](https://github.com/thinkingreed-inc/F-RevoCRM/issues/363) [不具合]ユーザー一覧の罫線が消えることがある
  - [#362](https://github.com/thinkingreed-inc/F-RevoCRM/issues/362) [不具合]活動のリストにToDoのステータスを表示していないと活動の完了アイコンが次の予定登録アイコンに切り替わらない
  - [#353](https://github.com/thinkingreed-inc/F-RevoCRM/issues/353) [不具合]ドキュメントのリスト表示の翻訳漏れ
  - [#350](https://github.com/thinkingreed-inc/F-RevoCRM/issues/350) [不具合]項目追加時に項目タイプを何回か切り替えると、デフォルト値の表示がおかしくなる
  - [#312](https://github.com/thinkingreed-inc/F-RevoCRM/issues/312) [不具合]ワークフローで値の更新を行う際に、更新先がメールアドレスタイプの際に、フィールド名をrawテキストと認識してしまう
  - [#307](https://github.com/thinkingreed-inc/F-RevoCRM/issues/307) [不具合] カレンダーの詳細編集画面で一部表示が乱れる箇所がある
  - [#287](https://github.com/thinkingreed-inc/F-RevoCRM/issues/287) [不具合] フォーム入力画面にて変更不可のデフォルト値が変更できてしまう
  - [#249](https://github.com/thinkingreed-inc/F-RevoCRM/issues/249) [不具合]案件をエクスポートした際に関連項目（ユーザー）の値が正しくない（ver7.3.3）
  - [#149](https://github.com/thinkingreed-inc/F-RevoCRM/issues/149) [不具合]半角で数字0を入力し保存した場合、編集画面で0の値が表示されずに空となっている。

### Contributors
Thank you for contributing!

<a href="https://github.com/Sota-Miyamoto"><img src="https://github.com/Sota-Miyamoto.png" title="Sota-Miyamoto" width="40" height="40" style="border-radius: 50%;"></a>
<a href="https://github.com/K-Haruto"><img src="https://github.com/K-Haruto.png" title="K-Haruto" width="40" height="40" style="border-radius: 50%;"></a>
<a href="https://github.com/kkouta"><img src="https://github.com/kkouta.png" title="kkouta" width="40" height="40" style="border-radius: 50%;"></a>
<a href="https://github.com/pavish69"><img src="https://github.com/pavish69.png" title="pavish69" width="40" height="40" style="border-radius: 50%;"></a>
<a href="https://github.com/Remicck"><img src="https://github.com/Remicck.png" title="Remicck" width="40" height="40" style="border-radius: 50%;"></a>

## F-RevoCRM7.3.5.1
前回提供したv7.3.5に不具合がありましたので、一部機能を無効化して不具合を修正しました。  
タグをご利用のお客様はこちらのパッチの適用をお願いします。

### パッチ適用方法
- ファイル、DBのバックアップを確実に取得してください
- 差分ファイルを上書き更新してください

### 主な変更点
- タグが付与されているレコードが保存できない不具合の修正
- revert #285 [不具合]タグのインポートができない

## F-RevoCRM7.3.5
### パッチ適用方法
- ファイル、DBのバックアップを確実に取得してください
- 差分ファイルを上書き更新してください
- 以下のURLにアクセスし、マイグレーションを実施してください。  
`https://example.com/frevocrm/index.php?module=Migration&view=Index&mode=step1`

### 主な変更点

* 機能改善
  - [#346](https://github.com/thinkingreed-inc/F-RevoCRM/issues/346) [要望]通貨項目にマイナス値を入力できるようにしてほしい
  - [#338](https://github.com/thinkingreed-inc/F-RevoCRM/issues/338) [要望]PDFテンプレートによるPDFエクスポートにて、複数レコードで一括エクスポートができるようにしてほしい
  - [#335](https://github.com/thinkingreed-inc/F-RevoCRM/issues/335) [要望]PDFテンプレートモジュールにて、各明細の行番号を表示したい。
  - [#303](https://github.com/thinkingreed-inc/F-RevoCRM/issues/303) [要望]見積もりなどの商品複数追加するUIでの、備考欄の横幅を全体に合わあせて広くする
  - [#285](https://github.com/thinkingreed-inc/F-RevoCRM/issues/285) [不具合]タグのインポートができない
  - [#237](https://github.com/thinkingreed-inc/F-RevoCRM/issues/237) [要望]見積書、発注書などに単位を表示したい
  - [#228](https://github.com/thinkingreed-inc/F-RevoCRM/issues/228) [要望] 概要画面の活動に担当者を表示してほしい

* 不具合
  - [#348](https://github.com/thinkingreed-inc/F-RevoCRM/issues/348) [不具合]顧客企業の概要画面が開くのが遅い
  - [#337](https://github.com/thinkingreed-inc/F-RevoCRM/issues/337) [不具合]文字列項目が多数含まれているモジュールにインポートした場合、インポートに失敗する。
  - [#336](https://github.com/thinkingreed-inc/F-RevoCRM/issues/336) [不具合]WebAPIのQuery処理で受注モジュールの明細行が最終行以外取得できない。
  - [#304](https://github.com/thinkingreed-inc/F-RevoCRM/issues/304) [不具合]タイトルの長いレコードを、別モジュールの関連から表示した際、「詳細」や「×」ボタンが表示されない。
  - [#295](https://github.com/thinkingreed-inc/F-RevoCRM/issues/295) [不具合]詳細画面のアイコンの背景色が消えている
  - [#290](https://github.com/thinkingreed-inc/F-RevoCRM/issues/290) [不具合]ユーザー一覧の”名前とメールアドレス ”の列がズレて表示される
  - [#284](https://github.com/thinkingreed-inc/F-RevoCRM/issues/284) [不具合]パスワード登録、変更の文字数制限が正常に機能していない
  - [#261](https://github.com/thinkingreed-inc/F-RevoCRM/issues/261) [不具合]ワークフローで値を更新すると最終更新者がシステム管理者になる
  - [#238](https://github.com/thinkingreed-inc/F-RevoCRM/issues/238) [不具合]見積書で入力した調整金額がPDF出力すると合計金額に反映されない。
  - [#153](https://github.com/thinkingreed-inc/F-RevoCRM/issues/153) [不具合]ブロック内のテキストエリアしかない場合の表示崩れ
  - [#94](https://github.com/thinkingreed-inc/F-RevoCRM/issues/94) [不具合]私の予定表で「繰り返しの予定の変更/削除」の「×」ボタンを押すと保存できなくなる
  - [#62](https://github.com/thinkingreed-inc/F-RevoCRM/issues/62) [不具合]ユーザー管理のユーザーの画面にて、パスワードの変更等の表示が埋もれている
  - [#381](https://github.com/thinkingreed-inc/F-RevoCRM/issues/381) [不具合]価格表モジュールでレポートを出力する際に、新規作成フィールドを扱うとエラーになる不具合の修正

* 翻訳
  - [#260](https://github.com/thinkingreed-inc/F-RevoCRM/issues/260) [不具合]レポートモジュールにおける日本語翻訳漏れ
  - [#259](https://github.com/thinkingreed-inc/F-RevoCRM/issues/259) [不具合]パスワードを日本語翻訳漏れ
  - [#253](https://github.com/thinkingreed-inc/F-RevoCRM/issues/253) [不具合]グループを作成時の日本語未翻訳箇所
  - [#311](https://github.com/thinkingreed-inc/F-RevoCRM/issues/311) [不具合]他の人がインポート中のときにインポートしようとする時に表示される文言の翻訳漏れ
  - [#203](https://github.com/thinkingreed-inc/F-RevoCRM/issues/203) [不具合]リスト作成時のエラーメッセージが未翻訳
  - [#88](https://github.com/thinkingreed-inc/F-RevoCRM/issues/88) [不具合]日本語と英語が混在した文章がある

* 環境
  - [#323](https://github.com/thinkingreed-inc/F-RevoCRM/issues/323) MySQLのDockerfileにnkfが含まれているため削除

* ドキュメンテーション
  - [#171](https://github.com/thinkingreed-inc/F-RevoCRM/issues/171) [要望]マイグレーションをコマンドライン側から叩きたい
  - [#34](https://github.com/thinkingreed-inc/F-RevoCRM/issues/34) [不具合]getTranslatedString関数だと、LanguageConverterで指定した変換がされない

### Contributors
Thank you for contributing!

<a href="https://github.com/Sota-Miyamoto"><img src="https://github.com/Sota-Miyamoto.png" title="Sota-Miyamoto" width="40" height="40" style="border-radius: 50%;"></a>
<a href="https://github.com/K-Haruto"><img src="https://github.com/K-Haruto.png" title="K-Haruto" width="40" height="40" style="border-radius: 50%;"></a>
<a href="https://github.com/pavish69"><img src="https://github.com/pavish69.png" title="pavish69" width="40" height="40" style="border-radius: 50%;"></a>
<a href="https://github.com/junmt"><img src="https://github.com/junmt.png" title="junmt" width="40" height="40" style="border-radius: 50%;"></a>
<a href="https://github.com/Remicck"><img src="https://github.com/Remicck.png" title="Remicck" width="40" height="40" style="border-radius: 50%;"></a>


## F-RevoCRM7.3.4
### パッチ適用方法
- 差分ファイルを上書き更新してください
- 以下のURLにアクセスし、マイグレーションを実施してください。  
`https://example.com/frevocrm/index.php?module=Migration&view=Index&mode=step1`

### 主な変更点

* 機能改善
  - #79 プロジェクトタスク「終了日」のクイック作成をデフォルトで有効にしてほしい
  - #194 プロジェクトの関連>マイルストーンで新規追加する際、プロジェクトを自動セットしてほしい
  - #155 Migration後の画面が英語表示
  - #98 日付条件の翻訳を改善

* 不具合修正
  - #244 見積の「項目の詳細」から送料を設定しても反映されない
  - #234 顧客企業の活動が二重表示されてしまう
  - #220 カスタマーポータルからファイルをダウンロードすると、空のファイルが送られる
  - #216 関連を開くとPHPのエラーが発生する
  - #205 TODO管理において、ユーザ選択およびステータスが保持されない
  - #201 00:00開始の予定を作成しようとすると終日にチェックが入ってしまう
  - #200 カレンダーの設定を12時間表記にすると、週次カレンダー上部の「終日エリア」から予定を作成するときに、終日フラグが入らない
  - #199 リストの複製をすると、項目と並び順の選択に余計な項目が設定される
  - #192 レポートで日付項目に対して「空である」などの条件を指定するとSQLエラーが発生する
  - #183 「ユーザー名の変更」モーダルの新ユーザー名が翻訳されていない
  - #181 「ユーザー名の変更」がパスワードがエラーで保存出来ない
  - #179 関連画面のコメントで編集を行うと改行が削除されたように見える
  - #173 削除した顧客担当者が関連の活動に残る
  - #172 コメントに自身が設定しているサムネイル画像（プロフィール画像）が表示されない
  - #169 作成した見積の合計金額と出力したPDFファイルの合計金額が1円違う
  - #161 システム設定画面でヘッダーが一部ずれる
  - #159 エクスポートした見積PDFの値引き額（貴社特別値引き）に反映されない
  - #130 F-RevoCRM6.Xから7.Xにマイグレーションした後、F-RevoCRM6.Xにて作成していた活動を削除すると、全活動が削除される
  - #123 項目タイプ関連、モジュール活動の項目で参照ボタンを押したら「権限がありません」と表示される。
  - #78 フィルターのデフォルト設定の不具合
  - #67 モジュールの詳細画面にて、コメントのアイコンサイズが小さい
  - #158 画面幅が狭いときドキュメントのアップロードモーダルが崩れる
  - #134 画面幅が狭い際にドキュメントとレポートでヘッダーがずれる
  - #213 ユーザーとユーザで表記ゆれがある

* その他修正
  - typo関連の修正
  - Migration時に実行時間の上限がなくなるように修正
  - #180 コミットメッセージの表記ゆれの改善

## F-RevoCRM7.3.3
### パッチ適用方法
- 差分ファイルを上書き更新してください
- 以下のURLにアクセスし、マイグレーションを実施してください。  
`https://example.com/frevocrm/index.php?module=Migration&view=Index&mode=step1`

### 主な変更点

* 機能改善
  - 選択されているリストの色を、見やすくなるように濃く変更（#139）
  - カレンダー通知用ポップアップの処理速度を改善（#99）
  - Webフォーム参照フィールドの値を、cf_xxx形式で表示するように改善（#91）
  - 関連項目として「ユーザー」を設定できるように改善（#32）
  - 初期インストールされるワークフローのワークフロー名を日本語に変更
  - 初期インストールされるレポートのレポート名を日本語に変更

* 不具合修正
  - カレンダーの招待ユーザーに送付されるicsファイルのタイムゾーンを、受信するユーザーに合わせるように修正（#121）
  - 上部検索エリアが適切に動かないケースの修正（#85, #80）
  - インライン編集を行い、キャンセルを行った後に再度編集を行い保存すると正常な値が保存されない不具合の修正（#95）
  - 顧客ポータルのURLが長い場合、枠をはみ出してしまう不具合の修正（#64, #61）
  - 繰り返し予定や招待予定を作成した場合、終日フラグが外れてしまう不具合の修正（#96）
  - ダッシュボードウィジェットのノートにて、URLに？が含まれている場合に切り取られて保存されてしまう不具合の修正（#48）
  - 活動に顧客担当者を複数名登録した後、詳細入力へ遷移すると顧客担当者が消えてしまう不具合の修正（#10）
  - 終日の予定を時間予定に変更した際に、終日フラグがはずれない不具合の修正
  - PDFを一括出力した場合に、顧客企業名をファイル名に含むように修正
  - デザイン調整（#114, #140, #125, #116, #83, #97, #71, #37, #33）、その他

* その他修正
  - 復数の日本語訳を追加（#72） 
  - DockerコンテナのタイムゾーンをJSTに変更（#154）
  - Docker環境でのインストール時の入力を簡易化するように修正
  - Docker環境下で必要なフォルダが生成されない不具合の修正
  - Docker環境にxdebug3をインストール
  - Docker環境を再起動時に自動で立ち上がるように修正
  - Pull Requestのテンプレートを作成
  - F-RevoCRMのIE11対応を、2022年4月以降非推奨とする文言の追加


## F-RevoCRM7.3.2
### パッチ適用方法
- 差分ファイルを上書き更新してください
- 以下のURLにアクセスし、マイグレーションを実施してください。  
`https://example.com/frevocrm/index.php?module=Migration&view=Index&mode=step1`

### 主な変更点

* 機能改善
  - ユーザーの初回ログイン時に、共有カレンダーのマイグループに所属するユーザーを、自身のみになるように改善
  - 製品モジュールのエクスポート画面の日本語和訳を追加(#31)
  - 項目編集の｢項目を表示｣の日本語和訳を追加(#43)
  - ドキュメントモジュールで「内部」としてURLを保存した際に、新しいタブでページが開くように修正
  - その他、ドキュメントでURLを指定したときの動作を改善
  - 見積、受注、発注、請求モジュールの編集画面にて、手数料が数値以外の場合は0円を設定するように修正
  - カレンダー表示画面にて、マウスオーバー時に表示される活動画面に「活動コピー」機能を追加

* 不具合修正
  - README.mdのアップデート手順に誤りがあったため修正
  - 概要欄や関連から活動を追加する際に、招待者が正常に登録されない不具合を修正
  - スマートフォン表示時に詳細画面で項目タイトルが右寄せになる不具合の修正(#2)
  - ドキュメントの詳細画面でURLを内部で保存するとハイパーリンクにならない問題を修正
  - 見積、受注、発注、請求モジュールの編集画面にて、課税対象地域を変更すると金額がNaNとなる不具合を修正
  - リストの関連リンクから別モジュールへ遷移した場合、左サイドバーのメニューがMARKETINGのものになる不具合の修正(#38)
  - 編集画面においてシステム管理者でないユーザーの場合、詳細情報の配置が崩れる問題を修正
  - Docker環境にてドキュメント保存用フォルダが無いことによってファイルアップロードができない不具合の修正(#5)
  - Docker環境にてJpegファイルがアップロードできない不具合の修正(#24) @zeroadster

* その他修正
  - README.mdに記載されているサンプルURLをexample.comに置換
  - インストーラーにて、環境変数を見て自動でDB設定が入るように修正

## F-RevoCRM7.3.1
### パッチ適用方法
- 差分ファイルを上書き更新してください
- 以下のURLにアクセスし、マイグレーションを実施してください。  
`https://example.com/frevocrm/index.php?module=Migration&view=Index&mode=step1`

### 主な変更点
* 機能改善
  - 日本語翻訳を複数追加
  - サイドバーアイコン部分の表示を改善
  - 個人アイコンを設定した際のアスペクト比を維持するように改善
  - チケットモジュール、FAQモジュールにて、画像を挿入した場合の表示を改善
  - チケットモジュール・FAQモジュールにて、画像が保存できないケースを改善
  - チケットモジュール・FAQモジュールにて、「イメージ」ボタンのプレビュー欄の表示を改善
  - 日報モジュールの「コメント」項目の文字数制限が250文字だった為、TEXT型に変更
  - コメント欄にて、PDFファイルをアップロードした時のプレビューの挙動を改善
  - プロジェクトモジュールの「チャート」画面にて、タスク名表示を改善
  - 活動登録時に時間の選択肢をキーボードで選択した場合の動作を改善
  - モバイル：日報モジュールの概要画面の更新履歴エリアにて、更新日時の表示を改善

* 不具合修正
  - 各モジュールの概要画面に表示される活動の曜日が全て木曜日となる不具合の修正
  - 一覧画面にて、最終更新者のユーザーを選択できない不具合の修正
  - メール送信可能な一覧からメール送信対象をチェックを付けてメール送信を行った際に、ランダムに1通のみメールが送信される不具合の修正
  - リード画面にて、関連メニューのメール部分に件数が表示されない不具合の修正
  - 一般ユーザーで、レポート表示時にエラーが発生する不具合の修正
  - 管理機能「企業の詳細」画面にて、画像がアップロードできないケースがある不具合の修正
  - 初期セットアップ時に日報が追加されない不具合の修正 ※本パッチ適用時に日報モジュールが追加されます

## F-RevoCRM7.3
### 主な変更点

* 機能追加
  - 見積、受注、請求、発注のPDFテンプレートを作成・編集できる機能を追加
  - システム設定に文言変更機能を追加
  - プロジェクトタスクのガントチャートを追加
  - グラフのダッシュボード表示を追加
  - デフォルトのダッシュボードを追加
  - ユーザー一覧に検索機能を追加
  - ユーザーのCSVインポート機能を追加
  - 関連データに対しての簡易検索機能を追加
  - Webフォーム取り込みに添付ファイルの取り込み機能を追加
  - 一覧画面にクイック表示の機能を追加
  - 案件からプロジェクトにコンバートできる機能を追加
  - メールコンバーターのメール自動紐付け機能を追加
  - フォロー機能を追加
  - RSS、ブックマーク機能を追加（復活）

* 機能改善
  - 画面デザインを刷新
  - 各文言を一般的な用語に変更
  - ユーザーのパスワードを8文字以上、アルファベット英数記号を含めるように制限
  - 一覧のスクロール時にヘッダ行が固定されるように改善（一覧画面のみ）
  - チケット（旧サポート依頼）、FAQ（旧回答事例）のテキストエリアの入力欄をリッチテキストに変更
  - 項目の種類に「関連」を追加（他モジュールを紐付ける項目）
  - リスト（旧フィルタ）の複製できるように改善
  - 共有リスト（旧フィルタ）の共有先の設定できるように改善
  - 「登録/編集」権限を「登録」と「編集」の権限に分離
  - 活動のCSVインポート機能を追加
  - 複数のダッシュボード管理に対応
  - ダッシュボードのウェジェットの表示サイズ変更を追加
  - 主要項目（旧概要）と関連一覧の表示設定の柔軟性を強化
  - 課税計算の設定を強化
  - タグ機能（旧タグクラウド）を強化
  - 関連するコメントをすべて表示できるように改善
  - 各レコードの入力元の表示を追加
  - 活動の繰り返し登録をした際に一括で削除や変更ができるように改善
  - ワークフローのレコードの登録、レコードの更新のアクションを強化
  - 初期表示のカレンダー表示（個人、共有、リスト）が選択できるように改善

以上

