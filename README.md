# css-direction 0.0.7

Css module of single purpose classes for direction

#### Stats

157 | 8 | 8
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-direction
```

#### With Git

```
git clone https://github.com/tachyons-css/css-direction
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-direction";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-direction">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   DIRECTION
*/
.ltr { direction: ltr; }
.rtl { direction: rtl; }
@media screen and (min-width: 48em) {
 .ltr-ns { direction: ltr; }
 .rtl-ns { direction: rtl; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .ltr-m { direction: ltr; }
 .rtl-m { direction: rtl; }
}
@media screen and (min-width: 64em) {
 .ltr-l { direction: ltr; }
 .rtl-l { direction: rtl; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC
