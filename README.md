<div align="center">
  <h1>facebook-chat-api</h1>
  <p>remod of ws3-fca</p>
</div>

<div align="center">
  <h2>how to use?</h2>
</div>

### firstly, install the package
```sh
npm i ruingl/facebook-chat-api 
```

### code example:

```js
// import fca
const fca = require("facebook-chat-api");

// setup fca
fca.logging(false);
// you can change this if you want
// to turn off log.

// login!
fca.login({
  // add your cookie in appState.
  appState: []
}, (err, api) => {
  // log the error
  if (err) console.error(err.error);

  // do what u want here
});
```
