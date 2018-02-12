<!-- Please do not edit this file. Edit the `blah` field in the `package.json` instead. If in doubt, open an issue. -->


# regex-parser

 [![Support me on Patreon][badge_patreon]][patreon] [![Buy me a book][badge_amazon]][amazon] [![PayPal][badge_paypal_donate]][paypal-donations] [![Ask me anything](https://img.shields.io/badge/ask%20me-anything-1abc9c.svg)](https://github.com/IonicaBizau/ama) [![Version](https://img.shields.io/npm/v/regex-parser.svg)](https://www.npmjs.com/package/regex-parser) [![Downloads](https://img.shields.io/npm/dt/regex-parser.svg)](https://www.npmjs.com/package/regex-parser)

> A module that parses a string as regular expression and returns the parsed value.

## :cloud: Installation

```sh
# Using npm
npm install --save regex-parser

# Using yarn
yarn add regex-parser
```


## :clipboard: Example



```js
// Dependencies
var RegexParser = require("regex-parser");

console.log(RegexParser("/^hi$/g"));
// => /^hi$/g
```



## :question: Get Help

There are few ways to get help:

 1. Please [post questions on Stack Overflow](https://stackoverflow.com/questions/ask). You can open issues with questions, as long you add a link to your Stack Overflow question.
 2. For bug reports and feature requests, open issues. :bug:

 3. For direct and quick help, you can [use Codementor](https://www.codementor.io/johnnyb). :rocket:



## :memo: Documentation


### `RegexParser(input)`
Parses a string input.

#### Params

- **String** `input`: The string input that should be parsed as regular expression.

#### Return
- **RegExp** The parsed regular expression.



## :yum: How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].


## :sparkling_heart: Support my projects

I open-source almost everything I can, and I try to reply everyone needing help using these projects. Obviously,
this takes time. You can integrate and use these projects in your applications *for free*! You can even change the source code and redistribute (even resell it).

However, if you get some profit from this or just want to encourage me to continue creating stuff, there are few ways you can do it:


 - Starring and sharing the projects you like :rocket:
 - [![Buy me a book][badge_amazon]][amazon]—I love books! I will remember you after years if you buy me one. :grin: :book:
 - [![PayPal][badge_paypal]][paypal-donations]—You can make one-time donations via PayPal. I'll probably buy a ~~coffee~~ tea. :tea:
 - [![Support me on Patreon][badge_patreon]][patreon]—Set up a recurring monthly donation and you will get interesting news about what I'm doing (things that I don't share with everyone).
 - **Bitcoin**—You can send me bitcoins at this address (or scanning the code below): `1P9BRsmazNQcuyTxEqveUsnf5CERdq35V6`

    ![](https://i.imgur.com/z6OQI95.png)


Thanks! :heart:


## :dizzy: Where is this library used?
If you are using this library in one of your projects, add it in this list. :sparkles:


 - [`adjust-sourcemap-loader`](https://github.com/bholloway/adjust-sourcemap-loader) (by bholloway)—Webpack loader that adjusts source maps
 - [`bible`](https://github.com/BibleJS/BibleApp)—Read the Holy Bible via the command line.
 - [`bible.js`](https://github.com/BibleJS/bible.js)—The Bible as a NPM module.
 - [`draper`](https://github.com/gajus/surgeon#readme) (by Gajus Kuizinas)—DOM extraction expression evaluator.
 - [`gene-js`](https://github.com/nicosommi/gene-js) (by nicosommi)—an add utility
 - [`leadconduit-custom`](https://github.com/activeprospect/leadconduit-integration-custom#readme) (by Alex Wolfe)—LeadConduit custom integration
 - [`panko`](https://npmjs.com/package/panko)—A collection of functions that make panko work. This package is for plugin creators, not users.
 - [`panko-cli`](https://npmjs.com/package/panko-cli)—A CLI-based project manager that reads from a list of separate profiles and allows various tasks to be completed.
 - [`rendition`](https://github.com/resin-io-modules/rendition#readme)—Resin Components Component
 - [`starts-with-emoji`](https://github.com/IonicaBizau/starts-with-emoji#readme)—Check if a string starts with an emoji.
 - [`statique`](https://github.com/IonicaBizau/statique)—A Node.JS static server module with built-in cache options and route features.
 - [`surgeon`](https://github.com/gajus/surgeon#readme) (by Gajus Kuizinas)—Declarative DOM extraction expression evaluator.
 - [`twing`](https://github.com/ericmorand/twing) (by Eric MORAND)—TypeScript port of the Twig templating language.

## :scroll: License

[MIT][license] © [Ionică Bizău][website]


[badge_patreon]: https://ionicabizau.github.io/badges/patreon.svg
[badge_amazon]: https://ionicabizau.github.io/badges/amazon.svg
[badge_paypal]: https://ionicabizau.github.io/badges/paypal.svg
[badge_paypal_donate]: https://ionicabizau.github.io/badges/paypal_donate.svg

[patreon]: https://www.patreon.com/ionicabizau
[amazon]: http://amzn.eu/hRo9sIZ
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(https%3A%2F%2Fionicabizau.net)&year=2014#license-mit
[website]: https://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md
