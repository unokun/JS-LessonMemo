# タイマー制作
## カウントダウンタイマー
* 秒の文字表記
* タイマー処理
** タイマー開始
** タイマー終了
** タイマーリセット

### 秒の文字(mm:ss)表示

[JavaScriptでゼロ埋めする方法](http://stabucky.com/wp/archives/4655)
```javascript
var a=5;
alert(("0"+a).slice(-2));
```

### タイマー処理
2重呼び出し防止。
