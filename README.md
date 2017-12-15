# copyTextPromise.js


## Usage

```js
const copyTextPromise = require('copyTextPromise.js');

button.addEventListener('click', () => {
	copyTextPromise('text').then(success => {
          success 
	  ?
	  console.log('text copy success and you can paste the text') 
	  :
	  console.log('broswer is no support copy, you can use another method to tip')
	});
});
```


## API

### copy(text)

Copy `text` to the clipboard.

Returns a `boolean` of whether it succeeded.

Must be called in response to a user gesture event, like `click` or `keyup`.


## Related

- [clipboardy](https://github.com/sindresorhus/clipboardy) - Access the system clipboard (copy/paste) in Node.js

