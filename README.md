# handy-snow-bookmarklets

Home ( / ):
```javascript
javascript: (function framer() {       var a = window.location.href;       var b = a.indexOf("://");       b = a.indexOf("/", b + 3) + 1;       var c = a.slice(0, b);       a = a.slice(b);       window.location.href = c + "";})();
```
