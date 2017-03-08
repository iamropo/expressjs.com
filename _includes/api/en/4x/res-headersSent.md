<h3 id='res.headersSent'>res.headersSent<span class="avaibility"></span> <span class="deprecated"></span></h3>

Boolean property that indicates if the app sent HTTP headers for the response.

```js
app.get('/', function (req, res) {
  console.log(res.headersSent); // false
  res.send('OK');
  console.log(res.headersSent); // true
});
```
