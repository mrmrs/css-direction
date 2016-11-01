# css-direction 1.0.6

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

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-direction
```

ssh:
```
git clone git@github.com:tachyons-css/css-direction.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-direction";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-direction@1.0.6/css/css-direction.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-direction">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

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

