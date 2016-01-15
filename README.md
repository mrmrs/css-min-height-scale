# css-min-height-scale 0.0.6

Css module of single purpose classes for min height scale

#### Stats

291 | 40 | 40
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-min-height-scale
```

#### With Git

```
git clone https://github.com/tachyons-css/css-min-height-scale
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-min-height-scale";
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
<link rel="stylesheet" href="path/to/module/css/css-min-height-scale">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   MIN HEIGHTS
*/
.mn-hi1 { min-height: 1rem; }
.mn-hi2 { min-height: 2rem; }
.mn-hi3 { min-height: 4rem; }
.mn-hi4 { min-height: 8rem; }
.mn-hi5 { min-height: 16rem; }
.mn-hi6 { min-height: 32rem; }
.mn-hi7 { min-height: 48rem; }
.mn-hi8 { min-height: 64rem; }
.mn-hi9 { min-height: 96rem; }
.mn-hi10 { min-height: 128rem; }
@media screen and (min-width: 48em) {
 .mn-hi1-ns { min-height: 1rem; }
 .mn-hi2-ns { min-height: 2rem; }
 .mn-hi3-ns { min-height: 4rem; }
 .mn-hi4-ns { min-height: 8rem; }
 .mn-hi5-ns { min-height: 16rem; }
 .mn-hi6-ns { min-height: 32rem; }
 .mn-hi7-ns { min-height: 48rem; }
 .mn-hi8-ns { min-height: 64rem; }
 .mn-hi9-ns { min-height: 96rem; }
 .mn-hi10-ns { min-height: 128rem; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .mn-hi1-m { min-height: 1rem; }
 .mn-hi2-m { min-height: 2rem; }
 .mn-hi3-m { min-height: 4rem; }
 .mn-hi4-m { min-height: 8rem; }
 .mn-hi5-m { min-height: 16rem; }
 .mn-hi6-m { min-height: 32rem; }
 .mn-hi7-m { min-height: 48rem; }
 .mn-hi8-m { min-height: 64rem; }
 .mn-hi9-m { min-height: 96rem; }
 .mn-hi10-m { min-height: 128rem; }
}
@media screen and (min-width: 64em) {
 .mn-hi1-l { min-height: 1rem; }
 .mn-hi2-l { min-height: 2rem; }
 .mn-hi3-l { min-height: 4rem; }
 .mn-hi4-l { min-height: 8rem; }
 .mn-hi5-l { min-height: 16rem; }
 .mn-hi6-l { min-height: 32rem; }
 .mn-hi7-l { min-height: 48rem; }
 .mn-hi8-l { min-height: 64rem; }
 .mn-hi9-l { min-height: 96rem; }
 .mn-hi10-l { min-height: 128rem; }
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

MIT

