# ShadowDragon

ShadowDragon is a javascript package where you can do the following:

● Random word (More info in the correct section)

● Email Generator (More info in the correct section)

## Installation

Use the package manager [npm](https://www.npmjs.com/) to install ShadowDragon.

```bash
npm install @devdex/ShadowDragon
```

## Usage
__**Random Word**__
```javascript
const { WordList } = require('@devdex/ShadowDragon');

var RandomWord = WordList();

console.log(RandomWord);
```

__**Email Generator**__
```javascript
const { EmailGenerator } = require('@devdex/ShadowDragon');

var Generate = EmailGenerator();

console.log(Generate);
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://devdex-djjr30-licences.glitch.me/shadow.html)
