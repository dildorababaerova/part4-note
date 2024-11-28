# part4-note
tutorial part 4

*  `status code 404 not found` 
*  Anything else you can see https://www.rfc-editor.org/rfc/rfc9110.html#name-404-not-found
* we respond to the request with the `status code 204 no content` and return no data with the response.
* The `json-parser` takes the JSON data of `a request`, `transforms` it `into a JavaScript object` and then `attaches` it to the `body` property of the request object `before the route handler` is called: `app.use(express.json())`
