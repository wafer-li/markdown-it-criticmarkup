# markdown-it-criticmarkup

markdown-it plugin for CriticMarkup support

See [criticmarkup user guide](http://criticmarkup.com/users-guide.php) for more CriticMarkup syntax

## Install

```bash
npm i markdown-it-cricticmarkup
```

## Usage

```js
var md = require('markdown-it')();

var critic = require('markdown-it-criticmarkup');

md.use(critic);

md.render('{++ins++}');
```
