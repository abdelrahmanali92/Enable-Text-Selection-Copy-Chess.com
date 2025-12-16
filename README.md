# Enable-Text-Selection-Copy-Chess.com
A short and simple code used in the Web Console to enable text selection and copying on the chess.com website.

```js
document.querySelectorAll('*').forEach(el => {
  el.style.userSelect = 'text';
  el.style.webkitUserSelect = 'text';
  el.style.msUserSelect = 'text';
});
```
