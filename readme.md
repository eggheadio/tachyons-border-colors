# tachyons-border-colors 4.2.3

Performance based css module.

### Stats

919 | 60 | 59
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-border-colors
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/tachyons-border-colors
```

ssh:
```
git clone git@github.com:tachyons-css/tachyons-border-colors.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-border-colors";
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
<link rel="stylesheet" href="http://unpkg.com/tachyons-border-colors@4.2.3/css/tachyons-border-colors.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons-border-colors">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/* Modified by Egghead */
/*

   Tachyons
   COLOR VARIABLES

   Grayscale
   - Solids
   - Transparencies
   Colors

*/
:root {/* Next iteration vars *//* Still active previous vars */ }
/*

   BORDER COLORS
   Docs: http://tachyons.io/docs/themes/borders/

   Border colors can be used to extend the base
   border classes ba,bt,bb,br,bl found in the _borders.css file.

   The base border class by default will set the color of the border
   to that of the current text color. These classes are for the cases
   where you desire for the text and border colors to be different.

   Base:
     b = border

   Modifiers:
   --color-name = each color variable name is also a border color name

*/
.b--black { border-color: #000; }
.b--white { border-color: #fff; }
.b--white-90 { border-color: rgba( 255, 255, 255, .9 ); }
.b--white-80 { border-color: rgba( 255, 255, 255, .8 ); }
.b--white-70 { border-color: rgba( 255, 255, 255, .7 ); }
.b--white-60 { border-color: rgba( 255, 255, 255, .6 ); }
.b--white-50 { border-color: rgba( 255, 255, 255, .5 ); }
.b--white-40 { border-color: rgba( 255, 255, 255, .4 ); }
.b--white-30 { border-color: rgba( 255, 255, 255, .3 ); }
.b--white-20 { border-color: rgba( 255, 255, 255, .2 ); }
.b--white-10 { border-color: rgba( 255, 255, 255, .1 ); }
.b--white-05 { border-color: rgba( 255, 255, 255, .05 ); }
.b--white-025 { border-color: rgba( 255, 255, 255, .025 ); }
.b--white-0125 { border-color: rgba( 255, 255, 255, .0125 ); }
.b--black-90 { border-color: rgba( 0, 0, 0, .9 ); }
.b--black-80 { border-color: rgba( 0, 0, 0, .8 ); }
.b--black-70 { border-color: rgba( 0, 0, 0, .7 ); }
.b--black-60 { border-color: rgba( 0, 0, 0, .6 ); }
.b--black-50 { border-color: rgba( 0, 0, 0, .5 ); }
.b--black-40 { border-color: rgba( 0, 0, 0, .4 ); }
.b--black-30 { border-color: rgba( 0, 0, 0, .3 ); }
.b--black-20 { border-color: rgba( 0, 0, 0, .2 ); }
.b--black-10 { border-color: rgba( 0, 0, 0, .1 ); }
.b--black-05 { border-color: rgba( 0, 0, 0, .05 ); }
.b--black-025 { border-color: rgba( 0, 0, 0, .025 ); }
.b--black-0125 { border-color: rgba( 0, 0, 0, .0125 ); }
.b--transparent { border-color: transparent; }
.b--white-secondary { border-color: #f8f8f8; }
.b--base { border-color: #21252d; }
.b--base-secondary { border-color: #141618; }
.b--base-light { border-color: #323439; }
.b--gray { border-color: #f4f7f9; }
.b--gray-secondary { border-color: #e2e3e7; }
.b--dark-gray { border-color: #63768d; }
.b--dark-gray-secondary { border-color: #b0b6be; }
.b--blue { border-color: #316aff; }
.b--blue-secondary { border-color: #2758b8; }
.b--dark-blue { border-color: #344055; }
.b--dark-blue-secondary { border-color: #273040; }
.b--green { border-color: #409b6b; }
.b--green-secondary { border-color: #36855b; }
.b--orange { border-color: #fd9126; }
.b--orange-secondary { border-color: #c97420; }
.b--red { border-color: #f0624d; }
.b--red-secondary { border-color: #c44c3a; }
.b--yellow { border-color: #fbc155; }
.b--yellow-secondary { border-color: #d2a043; }
/* Legacy classes */
.b--dark-navy { border-color: #141618; }
.b--navy { border-color: #21252d; }
.b--light-navy { border-color: #344055; }
.b--light-gray { border-color: #f8f8f8; }
.b--tag-gray { border-color: rgba( 255, 255, 255, .9 ); }
.b--dark-orange { border-color: #c97420; }
.b--tag-orange { border-color: rgba( 255, 255, 255, .7 ); }
.b--tag-blue { border-color: rgba( 255, 255, 255, .7 ); }
.b--dark-green { border-color: #36855b; }
.b--turquoise { border-color: #36855b; }
.b--tag-turquoise { border-color: rgba( 255, 255, 255, .7 ); }
.b--dark-red { border-color: #c44c3a; }
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

