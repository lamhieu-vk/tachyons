# tachyons-cli 1.0.11

Postprocess tachyons stylesheets

#### Stats

396 | 20 | 20
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-cli
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/tachyons-cli
```

ssh:
```
git clone git@github.com:tachyons-css/tachyons-cli.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-cli";
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
<link rel="stylesheet" href="http://unpkg.com/tachyons-cli@1.0.11/css/tachyons-cli.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons-cli">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*

   BORDER STYLES
   Docs: http://tachyons.io/docs/themes/borders/

   Depends on base border module in _borders.css

   Base:
     b = border-style

   Modifiers:
     --none   = none
     --dotted = dotted
     --dashed = dashed
     --solid  = solid

   Media Query Extensions:
     -ns = not-small
     -m  = medium       -ml = mobile landscape
     -l  = large

 */
.b--dotted { border-style: dotted; }
.b--dashed { border-style: dashed; }
.b--solid { border-style: solid; }
.b--none { border-style: none; }
@media screen and (min-width: 30em) {
 .b--dotted-ns { border-style: dotted; }
 .b--dashed-ns { border-style: dashed; }
 .b--solid-ns { border-style: solid; }
 .b--none-ns { border-style: none; }
}
@media screen and (min-width: 30em) and (max-width: 60em) {
 .b--dotted-m { border-style: dotted; }
 .b--dashed-m { border-style: dashed; }
 .b--solid-m { border-style: solid; }
 .b--none-m { border-style: none; }
}
@media screen and (max-width: 60em) and (orientation: landscape) {
 .b--dotted-ml { border-style: dotted; }
 .b--dashed-ml { border-style: dashed; }
 .b--solid-ml { border-style: solid; }
 .b--none-ml { border-style: none; }
}
@media screen and (min-width: 60em) {
 .b--dotted-l { border-style: dotted; }
 .b--dashed-l { border-style: dashed; }
 .b--solid-l { border-style: solid; }
 .b--none-l { border-style: none; }
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

