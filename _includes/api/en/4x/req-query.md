<h3 id='req.query'>req.query<span class="avaibility"></span> <span class="deprecated"></span></h3>

This property is an object containing a property for each query string parameter in the route.
If there is no query string, it is the empty object, `{}`.

```js
// GET /search?q=tobi+ferret
req.query.q
// => "tobi ferret"

// GET /shoes?order=desc&shoe[color]=blue&shoe[type]=converse
req.query.order
// => "desc"

req.query.shoe.color
// => "blue"

req.query.shoe.type
// => "converse"
```
