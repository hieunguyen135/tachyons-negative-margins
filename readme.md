# tachyons-negative-margins 1.0.0

negative-margins CSS module for Tachyons

#### Stats

922 | 140 | 140
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-negative-margins
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/tachyons-negative-margins
```

ssh:
```
git clone git@github.com:tachyons-css/tachyons-negative-margins.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-negative-margins";
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
<link rel="stylesheet" href="http://unpkg.com/tachyons-negative-margins@1.0.0/css/tachyons-negative-margins.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons-negative-margins">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/* Variables */
/* Spacing Scale - based on a ratio of 1:2 */
/*
   TACHYONS - NEGATIVE MARGINS

   Base:
     n = negative

   Modifiers:
     a = all
     t = top
     r = right
     b = bottom
     l = left

     1 = 1st step in spacing scale
     2 = 2nd step in spacing scale
     3 = 3rd step in spacing scale
     4 = 4th step in spacing scale
     5 = 5th step in spacing scale
     6 = 6th step in spacing scale
     7 = 7th step in spacing scale

   Media Query Extensions:
     -ns = not-small
     -m  = medium
     -l  = large

*/
.na1 { margin: calc( -1 * .25rem ); }
.na2 { margin: calc( -1 * .5rem ); }
.na3 { margin: calc( -1 * 1rem ); }
.na4 { margin: calc( -1 * 2rem ); }
.na5 { margin: calc( -1 * 4rem ); }
.na6 { margin: calc( -1 * 8rem ); }
.na7 { margin: calc( -1 * 16rem ); }
.nl1 { margin-left: calc( -1 * .25rem ); }
.nl2 { margin-left: calc( -1 * .5rem ); }
.nl3 { margin-left: calc( -1 * 1rem ); }
.nl4 { margin-left: calc( -1 * 2rem ); }
.nl5 { margin-left: calc( -1 * 4rem ); }
.nl6 { margin-left: calc( -1 * 8rem ); }
.nl7 { margin-left: calc( -1 * 16rem ); }
.nr1 { margin-right: calc( -1 * .25rem ); }
.nr2 { margin-right: calc( -1 * .5rem ); }
.nr3 { margin-right: calc( -1 * 1rem ); }
.nr4 { margin-right: calc( -1 * 2rem ); }
.nr5 { margin-right: calc( -1 * 4rem ); }
.nr6 { margin-right: calc( -1 * 8rem ); }
.nr7 { margin-right: calc( -1 * 16rem ); }
.nb1 { margin-bottom: calc( -1 * .25rem ); }
.nb2 { margin-bottom: calc( -1 * .5rem ); }
.nb3 { margin-bottom: calc( -1 * 1rem ); }
.nb4 { margin-bottom: calc( -1 * 2rem ); }
.nb5 { margin-bottom: calc( -1 * 4rem ); }
.nb6 { margin-bottom: calc( -1 * 8rem ); }
.nb7 { margin-bottom: calc( -1 * 16rem ); }
.nt1 { margin-top: calc( -1 * .25rem ); }
.nt2 { margin-top: calc( -1 * .5rem ); }
.nt3 { margin-top: calc( -1 * 1rem ); }
.nt4 { margin-top: calc( -1 * 2rem ); }
.nt5 { margin-top: calc( -1 * 4rem ); }
.nt6 { margin-top: calc( -1 * 8rem ); }
.nt7 { margin-top: calc( -1 * 16rem ); }
@media screen and (min-width: 30em) {
 .na1-ns { margin: calc( -1 * .25rem ); }
 .na2-ns { margin: calc( -1 * .5rem ); }
 .na3-ns { margin: calc( -1 * 1rem ); }
 .na4-ns { margin: calc( -1 * 2rem ); }
 .na5-ns { margin: calc( -1 * 4rem ); }
 .na6-ns { margin: calc( -1 * 8rem ); }
 .na7-ns { margin: calc( -1 * 16rem ); }
 .nl1-ns { margin-left: calc( -1 * .25rem ); }
 .nl2-ns { margin-left: calc( -1 * .5rem ); }
 .nl3-ns { margin-left: calc( -1 * 1rem ); }
 .nl4-ns { margin-left: calc( -1 * 2rem ); }
 .nl5-ns { margin-left: calc( -1 * 4rem ); }
 .nl6-ns { margin-left: calc( -1 * 8rem ); }
 .nl7-ns { margin-left: calc( -1 * 16rem ); }
 .nr1-ns { margin-right: calc( -1 * .25rem ); }
 .nr2-ns { margin-right: calc( -1 * .5rem ); }
 .nr3-ns { margin-right: calc( -1 * 1rem ); }
 .nr4-ns { margin-right: calc( -1 * 2rem ); }
 .nr5-ns { margin-right: calc( -1 * 4rem ); }
 .nr6-ns { margin-right: calc( -1 * 8rem ); }
 .nr7-ns { margin-right: calc( -1 * 16rem ); }
 .nb1-ns { margin-bottom: calc( -1 * .25rem ); }
 .nb2-ns { margin-bottom: calc( -1 * .5rem ); }
 .nb3-ns { margin-bottom: calc( -1 * 1rem ); }
 .nb4-ns { margin-bottom: calc( -1 * 2rem ); }
 .nb5-ns { margin-bottom: calc( -1 * 4rem ); }
 .nb6-ns { margin-bottom: calc( -1 * 8rem ); }
 .nb7-ns { margin-bottom: calc( -1 * 16rem ); }
 .nt1-ns { margin-top: calc( -1 * .25rem ); }
 .nt2-ns { margin-top: calc( -1 * .5rem ); }
 .nt3-ns { margin-top: calc( -1 * 1rem ); }
 .nt4-ns { margin-top: calc( -1 * 2rem ); }
 .nt5-ns { margin-top: calc( -1 * 4rem ); }
 .nt6-ns { margin-top: calc( -1 * 8rem ); }
 .nt7-ns { margin-top: calc( -1 * 16rem ); }
}
@media screen and (min-width: 30em) and (max-width: 60em) {
 .na1-m { margin: calc( -1 * .25rem ); }
 .na2-m { margin: calc( -1 * .5rem ); }
 .na3-m { margin: calc( -1 * 1rem ); }
 .na4-m { margin: calc( -1 * 2rem ); }
 .na5-m { margin: calc( -1 * 4rem ); }
 .na6-m { margin: calc( -1 * 8rem ); }
 .na7-m { margin: calc( -1 * 16rem ); }
 .nl1-m { margin-left: calc( -1 * .25rem ); }
 .nl2-m { margin-left: calc( -1 * .5rem ); }
 .nl3-m { margin-left: calc( -1 * 1rem ); }
 .nl4-m { margin-left: calc( -1 * 2rem ); }
 .nl5-m { margin-left: calc( -1 * 4rem ); }
 .nl6-m { margin-left: calc( -1 * 8rem ); }
 .nl7-m { margin-left: calc( -1 * 16rem ); }
 .nr1-m { margin-right: calc( -1 * .25rem ); }
 .nr2-m { margin-right: calc( -1 * .5rem ); }
 .nr3-m { margin-right: calc( -1 * 1rem ); }
 .nr4-m { margin-right: calc( -1 * 2rem ); }
 .nr5-m { margin-right: calc( -1 * 4rem ); }
 .nr6-m { margin-right: calc( -1 * 8rem ); }
 .nr7-m { margin-right: calc( -1 * 16rem ); }
 .nb1-m { margin-bottom: calc( -1 * .25rem ); }
 .nb2-m { margin-bottom: calc( -1 * .5rem ); }
 .nb3-m { margin-bottom: calc( -1 * 1rem ); }
 .nb4-m { margin-bottom: calc( -1 * 2rem ); }
 .nb5-m { margin-bottom: calc( -1 * 4rem ); }
 .nb6-m { margin-bottom: calc( -1 * 8rem ); }
 .nb7-m { margin-bottom: calc( -1 * 16rem ); }
 .nt1-m { margin-top: calc( -1 * .25rem ); }
 .nt2-m { margin-top: calc( -1 * .5rem ); }
 .nt3-m { margin-top: calc( -1 * 1rem ); }
 .nt4-m { margin-top: calc( -1 * 2rem ); }
 .nt5-m { margin-top: calc( -1 * 4rem ); }
 .nt6-m { margin-top: calc( -1 * 8rem ); }
 .nt7-m { margin-top: calc( -1 * 16rem ); }
}
@media screen and (min-width: 60em) {
 .na1-l { margin: calc( -1 * .25rem ); }
 .na2-l { margin: calc( -1 * .5rem ); }
 .na3-l { margin: calc( -1 * 1rem ); }
 .na4-l { margin: calc( -1 * 2rem ); }
 .na5-l { margin: calc( -1 * 4rem ); }
 .na6-l { margin: calc( -1 * 8rem ); }
 .na7-l { margin: calc( -1 * 16rem ); }
 .nl1-l { margin-left: calc( -1 * .25rem ); }
 .nl2-l { margin-left: calc( -1 * .5rem ); }
 .nl3-l { margin-left: calc( -1 * 1rem ); }
 .nl4-l { margin-left: calc( -1 * 2rem ); }
 .nl5-l { margin-left: calc( -1 * 4rem ); }
 .nl6-l { margin-left: calc( -1 * 8rem ); }
 .nl7-l { margin-left: calc( -1 * 16rem ); }
 .nr1-l { margin-right: calc( -1 * .25rem ); }
 .nr2-l { margin-right: calc( -1 * .5rem ); }
 .nr3-l { margin-right: calc( -1 * 1rem ); }
 .nr4-l { margin-right: calc( -1 * 2rem ); }
 .nr5-l { margin-right: calc( -1 * 4rem ); }
 .nr6-l { margin-right: calc( -1 * 8rem ); }
 .nr7-l { margin-right: calc( -1 * 16rem ); }
 .nb1-l { margin-bottom: calc( -1 * .25rem ); }
 .nb2-l { margin-bottom: calc( -1 * .5rem ); }
 .nb3-l { margin-bottom: calc( -1 * 1rem ); }
 .nb4-l { margin-bottom: calc( -1 * 2rem ); }
 .nb5-l { margin-bottom: calc( -1 * 4rem ); }
 .nb6-l { margin-bottom: calc( -1 * 8rem ); }
 .nb7-l { margin-bottom: calc( -1 * 16rem ); }
 .nt1-l { margin-top: calc( -1 * .25rem ); }
 .nt2-l { margin-top: calc( -1 * .5rem ); }
 .nt3-l { margin-top: calc( -1 * 1rem ); }
 .nt4-l { margin-top: calc( -1 * 2rem ); }
 .nt5-l { margin-top: calc( -1 * 4rem ); }
 .nt6-l { margin-top: calc( -1 * 8rem ); }
 .nt7-l { margin-top: calc( -1 * 16rem ); }
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

