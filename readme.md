# tachyons-svg-skins 0.0.1

Performance based css module.

#### Stats

790 | 78 | 78
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-svg-skins
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/lachlanjc/tachyons-svg-skins
```

ssh:
```
git clone git@github.com:lachlanjc/tachyons-svg-skins.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-svg-skins";
```

Then process the css using the [`tachyons-cli`](https://github.com/lachlanjc/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/tachyons-svg-skins@0.0.1/css/tachyons-svg-skins.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons-svg-skins">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*

   Tachyons
   COLOR VARIABLES

   Grayscale
   - Solids
   - Transparencies
   Colors

*/
/*

   SVG SKINS

   Classes for setting stroke and fill colors on SVG elements.

*/
/* Fill colors */
.fill-black { fill: #000; }
.fill-near-black { fill: #111; }
.fill-dark-gray { fill: #333; }
.fill-mid-gray { fill: #555; }
.fill-gray { fill: #777; }
.fill-silver { fill: #999; }
.fill-light-silver { fill: #aaa; }
.fill-moon-gray { fill: #ccc; }
.fill-light-gray { fill: #eee; }
.fill-near-white { fill: #f4f4f4; }
.fill-white { fill: #fff; }
.fill-transparent { fill: transparent; }
.fill-dark-red { fill: #e7040f; }
.fill-red { fill: #ff4136; }
.fill-light-red { fill: #ff725c; }
.fill-orange { fill: #ff6300; }
.fill-gold { fill: #ffb700; }
.fill-yellow { fill: #ffd700; }
.fill-light-yellow { fill: #fbf1a9; }
.fill-purple { fill: #5e2ca5; }
.fill-light-purple { fill: #a463f2; }
.fill-dark-pink { fill: #d5008f; }
.fill-hot-pink { fill: #ff41b4; }
.fill-pink { fill: #ff80cc; }
.fill-light-pink { fill: #ffa3d7; }
.fill-dark-green { fill: #137752; }
.fill-green { fill: #19a974; }
.fill-light-green { fill: #9eebcf; }
.fill-navy { fill: #001b44; }
.fill-dark-blue { fill: #00449e; }
.fill-blue { fill: #357edd; }
.fill-light-blue { fill: #96ccff; }
.fill-lightest-blue { fill: #cdecff; }
.fill-washed-blue { fill: #f6fffe; }
.fill-washed-green { fill: #e8fdf5; }
.fill-washed-yellow { fill: #fffceb; }
.fill-washed-red { fill: #ffdfdf; }
.fill-inherit { fill: inherit; }
.fill-current { fill: currentColor; }
/* Stoke colors */
.stroke-black { stroke: #000; }
.stroke-near-black { stroke: #111; }
.stroke-dark-gray { stroke: #333; }
.stroke-mid-gray { stroke: #555; }
.stroke-gray { stroke: #777; }
.stroke-silver { stroke: #999; }
.stroke-light-silver { stroke: #aaa; }
.stroke-moon-gray { stroke: #ccc; }
.stroke-light-gray { stroke: #eee; }
.stroke-near-white { stroke: #f4f4f4; }
.stroke-white { stroke: #fff; }
.stroke-transparent { stroke: transparent; }
.stroke-dark-red { stroke: #e7040f; }
.stroke-red { stroke: #ff4136; }
.stroke-light-red { stroke: #ff725c; }
.stroke-orange { stroke: #ff6300; }
.stroke-gold { stroke: #ffb700; }
.stroke-yellow { stroke: #ffd700; }
.stroke-light-yellow { stroke: #fbf1a9; }
.stroke-purple { stroke: #5e2ca5; }
.stroke-light-purple { stroke: #a463f2; }
.stroke-dark-pink { stroke: #d5008f; }
.stroke-hot-pink { stroke: #ff41b4; }
.stroke-pink { stroke: #ff80cc; }
.stroke-light-pink { stroke: #ffa3d7; }
.stroke-dark-green { stroke: #137752; }
.stroke-green { stroke: #19a974; }
.stroke-light-green { stroke: #9eebcf; }
.stroke-navy { stroke: #001b44; }
.stroke-dark-blue { stroke: #00449e; }
.stroke-blue { stroke: #357edd; }
.stroke-light-blue { stroke: #96ccff; }
.stroke-lightest-blue { stroke: #cdecff; }
.stroke-washed-blue { stroke: #f6fffe; }
.stroke-washed-green { stroke: #e8fdf5; }
.stroke-washed-yellow { stroke: #fffceb; }
.stroke-washed-red { stroke: #ffdfdf; }
.stroke-inherit { stroke: inherit; }
.stroke-current { stroke: currentColor; }
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
