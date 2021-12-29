# popup.js
Popup without jQuery

## Demos
https://ohno.github.io/popup.js/

## CDN
```
<script src="https://cdn.jsdelivr.net/gh/ohno/popup.js@1.0.1/popup.min.js"></script>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ohno/popup.js@1.0.1/popup.min.css">
```

## Usage

### Example 1
```
<script>popup("Hello World!");</script>
```

### Example 2
```
<button onClick='popup("Hello World!");'>popup</button>
```

### Example 3
```
<input id="input" value="TextTextTextTextTextText">
<button onClick='popup(document.getElementById("input").value);'>popup!</button>
```
