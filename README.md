


# meditation-app
参考：http://www.youtube.com/watch?v=oMBXdZzYqEk

##  準備
1.  [チュートリアル用のリポジトリ](https://github.com/developedbyed/meditation-app)をクローンする
2.  これから作成するので、soundsフォルダ・svgフォルダ・videoフォルダを残してファイルを削除

##  実装
1.   index.html
     *   ヘッダ部分作成（いつもの内容）
         *   読み込むcssはstyle.cssを指定
         * titleは適宜変更
     *  ボディ部分作成
         *   srcはapp.jsを指定
         *   今回必要なのは、3つの要素なのでその3つをとりあえず記載

2.   style.css
     *   全体の設定、アプリの設定、1で実装した3つの要素の設定を記載

3.  index.html
    *   3つの要素を実装する
        *   time-selectボタン　時間を選べる3種類のボタンを作成し、データは秒数とする
        *   player-container　クローンしたリポジトリに用意されているmp3ファイルを指定する
        *   **★　要確認：track-outlineとmoving-outlineのsvgファイルをコピーして貼り付ける**
        *   sound-picker　2つボタンを作成し、各々用意された音楽・アイコンと紐付ける
  
4.  style.css
    *   videoタグを非表示にする
    *   3つの要素のスタイルを調整する

5.  app.js

