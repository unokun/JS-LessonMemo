# DOM操作
## イベントハンドラ
DOM要素にEventListenerを追加する。
```javascript
       function event_alert(){
           alert("ボタンが押されました");
       }
       var button = document.getElementById("alert");
       button.addEventListener("click", event_alert, false);
```

### 処理の流れ
* addEventListernでイベント処理登録
* ユーザー操作(マウスでボタンクリック)
* clickイベント発生
* addEventListenerで登録した関数が実行される
* アラートが表示される

### イベント種類
* clock
* mouseover
* keydown
* load

## 実行タイミング
DOM要素ができていない場合には、実行できない。
特に、HTML読み込み時。
※) HTMLとJavaScriptはコードの上から順番に逐次実行される。

イベント処理は、window.onload(読み込み完了)の時に登録するのが良い。
```javascript
window.onload = function () {
   var button = document.getElementById('overwrite');
   button.addEventListener('click', text_overwrite, false);
}
```
無名関数の説明をする。
関数名を考える必要がない(重複を気にする必要がない)

## 要素の作成・追加
要素の登録は以下の手順で行う。
* 要素作成
* 属性、テキスト要素を設定
* 要素を追加(子要素・兄弟要素として)

## 一定間隔で繰り返し実行
タイマーを使うと画面が自動的に変化するのでプログラムらしくなる。
* タイマー開始(setInterval)
* タイマー終了(clearInterval)

## 課題
HTML要素の追加練習

## 課題(初級)
* HTML属性変更
* window.onloadでイベント登録

## 課題(中級)
* タイマー使用
* 文字列操作
例外処理として、文字列をすべて表示した後の処理も考える。

