# hatsuuma
<h2>はじめに</h2>
GoogleAppsScript(以下GAS)にテキストファイルの中身をコピー＆ペーストすることで初午が登録できます。<br>
hatsuumaの関数を実行して下さい。<br>
太陰暦や月の満ち欠け、祝祭日などは別の方が作っていたので当社としてはこちらを用意しました。<br>
よろしくお願い致します。<br>

<h2>機械やデータが苦手な方</h2>
導入することで、カレンダーに予定を追加できるものとお考え下さい。<br>
近くにパソコンに詳しい方がいらしたらお聞きになって下さい。<br>

<h2>Googleカレンダーをご存じでない方へ</h2>
Google社の開発したカレンダーアプリです。<br>
パソコンに詳しくなくても簡単に動かすことが出来ます。予定表として役立ちます。<br>

<h2>GASをご存じでない方へ</h2>
Google社の開発したワークスペースプラットフォームです。<br>
javascriptによって動いています。<br>

<h2>GASの起動方法</h2>
適当なGoogleスプレッドシートを開き、拡張機能からGASを選択し、<br>
最初の行に以下を入力する↓<br>

const address = "＊";<br>
let cal = CalendarApp.getCalendarById(address);

＊にはあなたのGoogleアカウントのメールアドレスを入れて下さい。

<h3>補足</h3>
60年分の登録が出来ます。知識の有る方は数値の変更などを行って下さい。<br>
別の方が用意している旧暦カレンダーや、六曜カレンダーなども入れておくと便利です。<br>
バグ報告はツイッターにてお願い致します。

<h3>その他</h3>
個人利用自由
