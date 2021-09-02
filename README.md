# NarouTextJavaScriptParser
小説家になろうのテキストをJavaScriptでhtmlに変換します。

## 動作環境

JavaScriptが動作するブラウザ

## 使い方

```javascript
let text = "｜山田太郎（やまだたろう）"
let html = narou2html(text)
```

```
console.log(html)
  <p><ruby>山田太郎<rt>やまだたろう</rt></ruby></p>
```
