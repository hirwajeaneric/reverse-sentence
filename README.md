# reverse-sentence

Reverse the words of a sentence

## Install
```sh
npm install @hirwa_jean_eric/reverse-sentence
```

## API

```js
require("reverse-sentence") => Function
reverse(sentence) => String
```

## Example
```js
const reverseSentence = require("reverse-sentence");

const sentence = "Hello Hirwa!";

const reversed = reverseSentence(sentence);

console.log(reversed) // Hirwa! Hello
```

## License

MIT