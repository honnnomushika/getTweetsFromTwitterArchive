日付や検索ワードでツイートを検索し、それに対するリプライも全部くっつけて表示するためのツールです。<br />
主に創作物の頭に特定タグをつけてSSを上げている人のバックアップ向け。

### 何が嬉しいのか
APIが使えなくても、アーカイブに含まれているツイートでさえあれば、リプライ含めた連投ツイートを簡単にまとめてコピーできるようになる。
※1ツイートに複数リプライがある多分岐は考慮していません

## 使い方
<ol>
    <li>twitter(X)からアーカイブをダウンロード</li>
    <li>ダウンロードしたアーカイブを解凍</li>
    <li>アーカイブ内のdataフォルダ内にtweets.jsがあるので、この冒頭の「window.YTD.tweets.part0」を「const tweets」に書き換える</li>
    <li>解凍したフォルダの直下に、 「データ抽出.html」 を置く。(dataやYour archive.htmlと並んでいればOK）
    <li> 「データ抽出.html」を開く</li>
    <li>設定欄で、日付や検索ワード、日付情報のフォーマットを任意で設定</li>
    <li>「実行」を押すと、下にズラッと抽出結果が出ます</li>
</ol>

### 利用イメージ
リプライが改行挟んでつながって出力されます。

https://github.com/user-attachments/assets/2885318d-30cd-456f-8c4a-72fad0ffbe92

Twitter上だとこうです
<img width="598" alt="Twitterスクリーンショット" src="https://github.com/user-attachments/assets/5d25150d-95af-431b-ba5d-5e6b66d88708" />
