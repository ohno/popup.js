# popup.js
Popup without jQuery

## Demos
https://ohno.github.io/popup.js/

## CDN
```
<script src="https://cdn.jsdelivr.net/gh/ohno/popup.js@1.0.0/popup.min.js"></script>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ohno/popup.js@1.0.0/popup.min.css">
```

## Usage

```
<script>popup("Hello World!");</script>
```

```
<button onClick='popup("Hello World!");'>ポップアップ表示</button>
```

```
<input id="input" value="ここに書いてある文字列を表示します。">
<button onClick='popup(document.getElementById("input").value);'>ポップアップ表示</button>
```
