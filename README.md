# hello-world
Hello World in Node.js using Express Framework.


<div class="alert alert-success">
Make sure you have installed express. If you have not then install it using below command:

<b>npm install express</b>

</div>

```
const express = require('express')
const app = express()

app.get('/', function (req, res) {
  res.send('Hello World!')
})

app.listen(3000, function () {
  console.log('Example app listening on port 3000!')
});
```
