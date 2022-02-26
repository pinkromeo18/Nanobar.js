# Nanobar.js
migration the nanobar.js

```js
/* usage */
var bar = new Nanobar({
  target:document.querySelector('#bar'),
  color:"#f37"
});
bar.go(50);
var prev = document.querySelector('#prev');
prev.textContent = bar.v;

```
