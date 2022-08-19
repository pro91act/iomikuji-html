# omikuji-html
html練習1　おみくじ

公開サイトのURL:
[おみくじのデモ](https://pro91act.github.io/omikuji-html/)
# おみくじ: JavaScript勉強するためのゲーム

## ■機能

画面の画像をクリックし、おみくじの画像の抽選が始まります。もう一回画像をクリックすると、ランダムで引かれたおみくじ画像が表示されます。

## ■主に利用したJavaScript知識

- ページから指定した名前の要素のオブジェクトの取得： 

    ```javascript
        document.getElementById(idName);
    ```

- 与える範囲にランダムの整数を取得する方法：
    
    ```javascript
        Math.floor(Math.random() * scope);
    ```

- タイマーの使い方：

    ```javascript
        myTimer = setInterval(function () {
            // 処理
    }, 100); // 空ける時間（ms）
    ```

- 配列の使い方
- 関数の作成及び使い方
- JSでHTMLの画像を入れ替える方法


## ■おみくじの画像
- [おみくじの検索結果 | かわいいフリー素材集 いらすとや](https://www.irasutoya.com/search?q=%E3%81%8A%E3%81%BF%E3%81%8F%E3%81%98)

## ■TODO

- おみくじ引いた履歴を保存し、画面に履歴リストを表示する機能を実装する