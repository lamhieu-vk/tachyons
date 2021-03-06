# tachyons-cli 1.0.11

Postprocess tachyons stylesheets

#### Stats

2984 | 501 | 942
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
/* Variables */
.a-zoom-in-out { -webkit-animation: zoom-in-out 1s ease, fade-in 1s ease; animation: zoom-in-out 1s ease, fade-in 1s ease; }
.a-zoom-out-in { -webkit-animation: zoom-out-in 1s ease, fade-in 1s ease; animation: zoom-out-in 1s ease, fade-in 1s ease; }
.a-fade-in { -webkit-animation: fade-in 1s ease; animation: fade-in 1s ease; }
.a-fade-out { -webkit-animation: fade-out 1s ease; animation: fade-out 1s ease; }
.a-fade-in-out { -webkit-animation: fade-in-out 1s ease; animation: fade-in-out 1s ease; }
.a-fade-out-in { -webkit-animation: fade-out-in 1s ease; animation: fade-out-in 1s ease; }
.a-slide-to-top { -webkit-animation: slide-to-top 1s ease, fade-in 1s ease; animation: slide-to-top 1s ease, fade-in 1s ease; }
.a-slide-to-right { -webkit-animation: slide-to-right 1s ease, fade-in 1s ease; animation: slide-to-right 1s ease, fade-in 1s ease; }
.a-slide-to-bottom { -webkit-animation: slide-to-bottom 1s ease, fade-in 1s ease; animation: slide-to-bottom 1s ease, fade-in 1s ease; }
.a-slide-to-left { -webkit-animation: slide-to-left 1s ease, fade-in 1s ease; animation: slide-to-left 1s ease, fade-in 1s ease; }
.a-slide-toggle-top { -webkit-animation: slide-toggle-top 1s ease, fade-in 1s ease; animation: slide-toggle-top 1s ease, fade-in 1s ease; }
.a-slide-toggle-right { -webkit-animation: slide-toggle-right 1s ease, fade-in 1s ease; animation: slide-toggle-right 1s ease, fade-in 1s ease; }
.a-slide-toggle-bottom { -webkit-animation: slide-toggle-bottom 1s ease, fade-in 1s ease; animation: slide-toggle-bottom 1s ease, fade-in 1s ease; }
.a-slide-toggle-right { -webkit-animation: slide-toggle-right 1s ease, fade-in 1s ease; animation: slide-toggle-right 1s ease, fade-in 1s ease; }
.a-shake { -webkit-animation: shake 1s ease, fade-in 1s ease; animation: shake 1s ease, fade-in 1s ease; }
.a-wobble { -webkit-animation: wobble 1s ease, fade-in 1s ease; animation: wobble 1s ease, fade-in 1s ease; }
.a-rotate { -webkit-animation: rotate 1s ease, fade-in 1s ease; animation: rotate 1s ease, fade-in 1s ease; }
.a-tilt-right { -webkit-animation: tilt-right 1s ease, fade-in 1s ease; animation: tilt-right 1s ease, fade-in 1s ease; }
.a-tilt-left { -webkit-animation: tilt-left 1s ease, fade-in 1s ease; animation: tilt-left 1s ease, fade-in 1s ease; }
.a-restart.e-tigger, .a-restart.e-active:active, .a-restart.e-hover:hover { -webkit-animation-name: none; animation-name: none; }
.a-vf { -webkit-animation-duration: .25s; animation-duration: .25s; }
.a-f { -webkit-animation-duration: .5s; animation-duration: .5s; }
.a-n { -webkit-animation-duration: 1s; animation-duration: 1s; }
.a-s { -webkit-animation-duration: 2s; animation-duration: 2s; }
.a-vs { -webkit-animation-duration: 2.5s; animation-duration: 2.5s; }
.a-bs { -webkit-animation-duration: 3s; animation-duration: 3s; }
.a-ss { -webkit-animation-duration: 5s; animation-duration: 5s; }
.a-normal { -webkit-animation-direction: normal; animation-direction: normal; }
.a-reverse { -webkit-animation-direction: reverse; animation-direction: reverse; }
.a-alternate { -webkit-animation-direction: alternate; animation-direction: alternate; }
.a-alternate-reverse { -webkit-animation-direction: alternate-reverse; animation-direction: alternate-reverse; }
.a-ease { -webkit-animation-timing-function: ease; animation-timing-function: ease; }
.a-ease-in { -webkit-animation-timing-function: ease-in; animation-timing-function: ease-in; }
.a-ease-out { -webkit-animation-timing-function: ease-out; animation-timing-function: ease-out; }
.a-ease-in-out { -webkit-animation-timing-function: ease-in-out; animation-timing-function: ease-in-out; }
.a-linear { -webkit-animation-timing-function: linear; animation-timing-function: linear; }
.a-step-start { -webkit-animation-timing-function: step-start; animation-timing-function: step-start; }
.a-step-end { -webkit-animation-timing-function: step-end; animation-timing-function: step-end; }
.a-infinite { -webkit-animation-iteration-count: infinite; animation-iteration-count: infinite; }
.a-2s { -webkit-animation-iteration-count: 2; animation-iteration-count: 2; }
.a-3s { -webkit-animation-iteration-count: 3; animation-iteration-count: 3; }
.a-4s { -webkit-animation-iteration-count: 4; animation-iteration-count: 4; }
.a-5s { -webkit-animation-iteration-count: 5; animation-iteration-count: 5; }
.a-10s { -webkit-animation-iteration-count: 10; animation-iteration-count: 10; }
.a-paused { -webkit-animation-play-state: paused; animation-play-state: paused; }
.a-running { -webkit-animation-play-state: running; animation-play-state: running; }
.a-fill-none { -webkit-animation-fill-mode: none; animation-fill-mode: none; }
.a-fill-forwards { -webkit-animation-fill-mode: forwards; animation-fill-mode: forwards; }
.a-fill-backwards { -webkit-animation-fill-mode: backwards; animation-fill-mode: backwards; }
.a-fill-both { -webkit-animation-fill-mode: both; animation-fill-mode: both; }
.a-delay-vf { -webkit-animation-delay: .25s; animation-delay: .25s; }
.a-delay-f { -webkit-animation-delay: .5s; animation-delay: .5s; }
.a-delay-n { -webkit-animation-delay: 1s; animation-delay: 1s; }
.a-delay-s { -webkit-animation-delay: 2s; animation-delay: 2s; }
.a-delay-vs { -webkit-animation-delay: 2.5s; animation-delay: 2.5s; }
.a--zoom-in-out { -webkit-animation-name: zoom-in-out; animation-name: zoom-in-out; }
.a--zoom-out-in { -webkit-animation-name: zoom-out-in; animation-name: zoom-out-in; }
.a--fade-in { -webkit-animation-name: fade-in; animation-name: fade-in; }
.a--fade-out { -webkit-animation-name: fade-out; animation-name: fade-out; }
.a--fade-in-out { -webkit-animation-name: fade-in-out; animation-name: fade-in-out; }
.a--fade-out-in { -webkit-animation-name: fade-out-in; animation-name: fade-out-in; }
.a--slide-to-top { -webkit-animation-name: slide-to-top; animation-name: slide-to-top; }
.a--slide-to-right { -webkit-animation-name: slide-to-right; animation-name: slide-to-right; }
.a--slide-to-bottom { -webkit-animation-name: slide-to-bottom; animation-name: slide-to-bottom; }
.a--slide-to-left { -webkit-animation-name: slide-to-left; animation-name: slide-to-left; }
.a--shake { -webkit-animation-name: shake; animation-name: shake; }
.a--wobble { -webkit-animation-name: wobble; animation-name: wobble; }
.a--rotate { -webkit-animation-name: rotate; animation-name: rotate; }
.a--tilt-right { -webkit-animation-name: tilt-right; animation-name: tilt-right; }
.a--tilt-left { -webkit-animation-name: tilt-left; animation-name: tilt-left; }
.a-none { -webkit-animation: none; animation: none; }
@-webkit-keyframes zoom-in-out {
 0% { -webkit-transform: scale( 1 ); transform: scale( 1 ); }
 50% { -webkit-transform: scale( 1.2 ); transform: scale( 1.2 ); }
 100% { -webkit-transform: scale( 1 ); transform: scale( 1 ); }
}
@keyframes zoom-in-out {
 0% { -webkit-transform: scale( 1 ); transform: scale( 1 ); }
 50% { -webkit-transform: scale( 1.2 ); transform: scale( 1.2 ); }
 100% { -webkit-transform: scale( 1 ); transform: scale( 1 ); }
}
@-webkit-keyframes zoom-out-in {
 0% { -webkit-transform: scale( 1 ); transform: scale( 1 ); }
 50% { -webkit-transform: scale( .7 ); transform: scale( .7 ); }
 100% { -webkit-transform: scale( 1 ); transform: scale( 1 ); }
}
@keyframes zoom-out-in {
 0% { -webkit-transform: scale( 1 ); transform: scale( 1 ); }
 50% { -webkit-transform: scale( .7 ); transform: scale( .7 ); }
 100% { -webkit-transform: scale( 1 ); transform: scale( 1 ); }
}
@-webkit-keyframes slide-to-top {
 0% { -webkit-transform: translateY( 5em ); transform: translateY( 5em ); }
 100% { -webkit-transform: translateY( 0 ); transform: translateY( 0 ); }
}
@keyframes slide-to-top {
 0% { -webkit-transform: translateY( 5em ); transform: translateY( 5em ); }
 100% { -webkit-transform: translateY( 0 ); transform: translateY( 0 ); }
}
@-webkit-keyframes fade-in {
 0% { opacity: 0; }
 100% { opacity: 1; }
}
@keyframes fade-in {
 0% { opacity: 0; }
 100% { opacity: 1; }
}
@-webkit-keyframes fade-out {
 0% { opacity: 1; }
 100% { opacity: 0; }
}
@keyframes fade-out {
 0% { opacity: 1; }
 100% { opacity: 0; }
}
@-webkit-keyframes fade-out-in {
 0% { opacity: 1; }
 50% { opacity: .2; }
 100% { opacity: 1; }
}
@keyframes fade-out-in {
 0% { opacity: 1; }
 50% { opacity: .2; }
 100% { opacity: 1; }
}
@-webkit-keyframes fade-in-out {
 0% { opacity: 0; }
 50% { opacity: .8; }
 100% { opacity: 0; }
}
@keyframes fade-in-out {
 0% { opacity: 0; }
 50% { opacity: .8; }
 100% { opacity: 0; }
}
@keyframes slide-to-top {
 0% { -webkit-transform: translateY( 5em ); transform: translateY( 5em ); }
 100% { -webkit-transform: translateY( 0 ); transform: translateY( 0 ); }
}
@-webkit-keyframes slide-to-right {
 0% { -webkit-transform: translateX( -5em ); transform: translateX( -5em ); }
 100% { -webkit-transform: translateX( 0 ); transform: translateX( 0 ); }
}
@keyframes slide-to-right {
 0% { -webkit-transform: translateX( -5em ); transform: translateX( -5em ); }
 100% { -webkit-transform: translateX( 0 ); transform: translateX( 0 ); }
}
@-webkit-keyframes slide-to-bottom {
 0% { -webkit-transform: translateY( -5em ); transform: translateY( -5em ); }
 100% { -webkit-transform: translateY( 0 ); transform: translateY( 0 ); }
}
@keyframes slide-to-bottom {
 0% { -webkit-transform: translateY( -5em ); transform: translateY( -5em ); }
 100% { -webkit-transform: translateY( 0 ); transform: translateY( 0 ); }
}
@-webkit-keyframes slide-to-left {
 0% { -webkit-transform: translateX( 5em ); transform: translateX( 5em ); }
 100% { -webkit-transform: translateX( 0 ); transform: translateX( 0 ); }
}
@keyframes slide-to-left {
 0% { -webkit-transform: translateX( 5em ); transform: translateX( 5em ); }
 100% { -webkit-transform: translateX( 0 ); transform: translateX( 0 ); }
}
@-webkit-keyframes slide-toggle-top {
 0% { -webkit-transform: translateY( 0 ); transform: translateY( 0 ); }
 50% { -webkit-transform: translateY( -2.5em ); transform: translateY( -2.5em ); }
 100% { -webkit-transform: translateY( 0 ); transform: translateY( 0 ); }
}
@keyframes slide-toggle-top {
 0% { -webkit-transform: translateY( 0 ); transform: translateY( 0 ); }
 50% { -webkit-transform: translateY( -2.5em ); transform: translateY( -2.5em ); }
 100% { -webkit-transform: translateY( 0 ); transform: translateY( 0 ); }
}
@-webkit-keyframes slide-toggle-right {
 0% { -webkit-transform: translateX( 0 ); transform: translateX( 0 ); }
 50% { -webkit-transform: translateX( 2.5em ); transform: translateX( 2.5em ); }
 100% { -webkit-transform: translateX( 0 ); transform: translateX( 0 ); }
}
@keyframes slide-toggle-right {
 0% { -webkit-transform: translateX( 0 ); transform: translateX( 0 ); }
 50% { -webkit-transform: translateX( 2.5em ); transform: translateX( 2.5em ); }
 100% { -webkit-transform: translateX( 0 ); transform: translateX( 0 ); }
}
@-webkit-keyframes slide-toggle-bottom {
 0% { -webkit-transform: translateY( 0 ); transform: translateY( 0 ); }
 50% { -webkit-transform: translateY( 2.5em ); transform: translateY( 2.5em ); }
 100% { -webkit-transform: translateY( 0 ); transform: translateY( 0 ); }
}
@keyframes slide-toggle-bottom {
 0% { -webkit-transform: translateY( 0 ); transform: translateY( 0 ); }
 50% { -webkit-transform: translateY( 2.5em ); transform: translateY( 2.5em ); }
 100% { -webkit-transform: translateY( 0 ); transform: translateY( 0 ); }
}
@-webkit-keyframes slide-toggle-left {
 0% { -webkit-transform: translateX( 0 ); transform: translateX( 0 ); }
 50% { -webkit-transform: translateX( -2.5em ); transform: translateX( -2.5em ); }
 100% { -webkit-transform: translateX( 0 ); transform: translateX( 0 ); }
}
@keyframes slide-toggle-left {
 0% { -webkit-transform: translateX( 0 ); transform: translateX( 0 ); }
 50% { -webkit-transform: translateX( -2.5em ); transform: translateX( -2.5em ); }
 100% { -webkit-transform: translateX( 0 ); transform: translateX( 0 ); }
}
@-webkit-keyframes shake {
 10%, 90% { -webkit-transform: translate3d( -0.025rem, 0, 0 ); transform: translate3d( -0.025rem, 0, 0 ); }
 20%, 80% { -webkit-transform: translate3d( .5rem, 0, 0 ); transform: translate3d( .5rem, 0, 0 ); }
 30%, 50%, 70% { -webkit-transform: translate3d( -1rem, 0, 0 ); transform: translate3d( -1rem, 0, 0 ); }
 40%, 60% { -webkit-transform: translate3d( 1rem, 0, 0 ); transform: translate3d( 1rem, 0, 0 ); }
}
@keyframes shake {
 10%, 90% { -webkit-transform: translate3d( -0.025rem, 0, 0 ); transform: translate3d( -0.025rem, 0, 0 ); }
 20%, 80% { -webkit-transform: translate3d( .5rem, 0, 0 ); transform: translate3d( .5rem, 0, 0 ); }
 30%, 50%, 70% { -webkit-transform: translate3d( -1rem, 0, 0 ); transform: translate3d( -1rem, 0, 0 ); }
 40%, 60% { -webkit-transform: translate3d( 1rem, 0, 0 ); transform: translate3d( 1rem, 0, 0 ); }
}
@-webkit-keyframes wobble {
 16.65% { -webkit-transform: translateY( 2rem ); transform: translateY( 2rem ); }
 33.3% { -webkit-transform: translateY( -1.5rem ); transform: translateY( -1.5rem ); }
 49.95% { -webkit-transform: translateY( 1rem ); transform: translateY( 1rem ); }
 66.6% { -webkit-transform: translateY( -0.5rem ); transform: translateY( -0.5rem ); }
 83.25% { -webkit-transform: translateY( .25rem ); transform: translateY( .25rem ); }
 100% { -webkit-transform: translateY( 0 ); transform: translateY( 0 ); }
}
@keyframes wobble {
 16.65% { -webkit-transform: translateY( 2rem ); transform: translateY( 2rem ); }
 33.3% { -webkit-transform: translateY( -1.5rem ); transform: translateY( -1.5rem ); }
 49.95% { -webkit-transform: translateY( 1rem ); transform: translateY( 1rem ); }
 66.6% { -webkit-transform: translateY( -0.5rem ); transform: translateY( -0.5rem ); }
 83.25% { -webkit-transform: translateY( .25rem ); transform: translateY( .25rem ); }
 100% { -webkit-transform: translateY( 0 ); transform: translateY( 0 ); }
}
@-webkit-keyframes rotate {
 0% { -webkit-transform: rotate( 0deg ); transform: rotate( 0deg ); }
 100% { -webkit-transform: rotate( 360deg ); transform: rotate( 360deg ); }
}
@keyframes rotate {
 0% { -webkit-transform: rotate( 0deg ); transform: rotate( 0deg ); }
 100% { -webkit-transform: rotate( 360deg ); transform: rotate( 360deg ); }
}
@-webkit-keyframes tilt-right {
 0% { -webkit-transform: rotate( 0 ) scale( 1 ); transform: rotate( 0 ) scale( 1 ); }
 50% { -webkit-transform: rotate( 15deg ) scale( 1.2 ); transform: rotate( 15deg ) scale( 1.2 ); }
 100% { -webkit-transform: rotate( 0 ) scale( 1 ); transform: rotate( 0 ) scale( 1 ); }
}
@keyframes tilt-right {
 0% { -webkit-transform: rotate( 0 ) scale( 1 ); transform: rotate( 0 ) scale( 1 ); }
 50% { -webkit-transform: rotate( 15deg ) scale( 1.2 ); transform: rotate( 15deg ) scale( 1.2 ); }
 100% { -webkit-transform: rotate( 0 ) scale( 1 ); transform: rotate( 0 ) scale( 1 ); }
}
@-webkit-keyframes tilt-left {
 0% { -webkit-transform: rotate( 0 ) scale( 1 ); transform: rotate( 0 ) scale( 1 ); }
 50% { -webkit-transform: rotate( -15deg ) scale( 1.2 ); transform: rotate( -15deg ) scale( 1.2 ); }
 100% { -webkit-transform: rotate( 0 ) scale( 1 ); transform: rotate( 0 ) scale( 1 ); }
}
@keyframes tilt-left {
 0% { -webkit-transform: rotate( 0 ) scale( 1 ); transform: rotate( 0 ) scale( 1 ); }
 50% { -webkit-transform: rotate( -15deg ) scale( 1.2 ); transform: rotate( -15deg ) scale( 1.2 ); }
 100% { -webkit-transform: rotate( 0 ) scale( 1 ); transform: rotate( 0 ) scale( 1 ); }
}
@media screen and (min-width: 30em) {
 .a-zoom-in-out-ns { -webkit-animation: zoom-in-out 1s ease, fade-in 1s ease; animation: zoom-in-out 1s ease, fade-in 1s ease; }
 .a-zoom-out-in-ns { -webkit-animation: zoom-out-in 1s ease, fade-in 1s ease; animation: zoom-out-in 1s ease, fade-in 1s ease; }
 .a-fade-in-ns { -webkit-animation: fade-in 1s ease; animation: fade-in 1s ease; }
 .a-fade-out-ns { -webkit-animation: fade-out 1s ease; animation: fade-out 1s ease; }
 .a-fade-in-out-ns { -webkit-animation: fade-in-out 1s ease; animation: fade-in-out 1s ease; }
 .a-fade-out-in-ns { -webkit-animation: fade-out-in 1s ease; animation: fade-out-in 1s ease; }
 .a-slide-to-top-ns { -webkit-animation: slide-to-top 1s ease, fade-in 1s ease; animation: slide-to-top 1s ease, fade-in 1s ease; }
 .a-slide-to-right-ns { -webkit-animation: slide-to-right 1s ease, fade-in 1s ease; animation: slide-to-right 1s ease, fade-in 1s ease; }
 .a-slide-to-bottom-ns { -webkit-animation: slide-to-bottom 1s ease, fade-in 1s ease; animation: slide-to-bottom 1s ease, fade-in 1s ease; }
 .a-slide-to-left-ns { -webkit-animation: slide-to-left 1s ease, fade-in 1s ease; animation: slide-to-left 1s ease, fade-in 1s ease; }
 .a-slide-toggle-top-ns { -webkit-animation: slide-toggle-top 1s ease, fade-in 1s ease; animation: slide-toggle-top 1s ease, fade-in 1s ease; }
 .a-slide-toggle-right-ns { -webkit-animation: slide-toggle-right 1s ease, fade-in 1s ease; animation: slide-toggle-right 1s ease, fade-in 1s ease; }
 .a-slide-toggle-bottom-ns { -webkit-animation: slide-toggle-bottom 1s ease, fade-in 1s ease; animation: slide-toggle-bottom 1s ease, fade-in 1s ease; }
 .a-slide-toggle-right-ns { -webkit-animation: slide-toggle-right 1s ease, fade-in 1s ease; animation: slide-toggle-right 1s ease, fade-in 1s ease; }
 .a-shake-ns { -webkit-animation: shake 1s ease, fade-in 1s ease; animation: shake 1s ease, fade-in 1s ease; }
 .a-wobble-ns { -webkit-animation: wobble 1s ease, fade-in 1s ease; animation: wobble 1s ease, fade-in 1s ease; }
 .a-rotate-ns { -webkit-animation: rotate 1s ease, fade-in 1s ease; animation: rotate 1s ease, fade-in 1s ease; }
 .a-tilt-right-ns { -webkit-animation: tilt-right 1s ease, fade-in 1s ease; animation: tilt-right 1s ease, fade-in 1s ease; }
 .a-tilt-left-ns { -webkit-animation: tilt-left 1s ease, fade-in 1s ease; animation: tilt-left 1s ease, fade-in 1s ease; }
 .a-restart-ns.e-tigger, .a-restart-ns.e-active:active,
 .a-restart-ns.e-hover:hover { -webkit-animation-name: none; animation-name: none; }
 .a-vf-ns { -webkit-animation-duration: .25s; animation-duration: .25s; }
 .a-f-ns { -webkit-animation-duration: .5s; animation-duration: .5s; }
 .a-n-ns { -webkit-animation-duration: 1s; animation-duration: 1s; }
 .a-s-ns { -webkit-animation-duration: 2s; animation-duration: 2s; }
 .a-vs-ns { -webkit-animation-duration: 2.5s; animation-duration: 2.5s; }
 .a-bs-ns { -webkit-animation-duration: 3s; animation-duration: 3s; }
 .a-ss-ns { -webkit-animation-duration: 5s; animation-duration: 5s; }
 .a-normal-ns { -webkit-animation-direction: normal; animation-direction: normal; }
 .a-reverse-ns { -webkit-animation-direction: reverse; animation-direction: reverse; }
 .a-alternate-ns { -webkit-animation-direction: alternate; animation-direction: alternate; }
 .a-alternate-reverse-ns { -webkit-animation-direction: alternate-reverse; animation-direction: alternate-reverse; }
 .a-ease-ns { -webkit-animation-timing-function: ease; animation-timing-function: ease; }
 .a-ease-in-ns { -webkit-animation-timing-function: ease-in; animation-timing-function: ease-in; }
 .a-ease-out-ns { -webkit-animation-timing-function: ease-out; animation-timing-function: ease-out; }
 .a-ease-in-out-ns { -webkit-animation-timing-function: ease-in-out; animation-timing-function: ease-in-out; }
 .a-linear-ns { -webkit-animation-timing-function: linear; animation-timing-function: linear; }
 .a-step-start-ns { -webkit-animation-timing-function: step-start; animation-timing-function: step-start; }
 .a-step-end-ns { -webkit-animation-timing-function: step-end; animation-timing-function: step-end; }
 .a-infinite-ns { -webkit-animation-iteration-count: infinite; animation-iteration-count: infinite; }
 .a-2s-ns { -webkit-animation-iteration-count: 2; animation-iteration-count: 2; }
 .a-3s-ns { -webkit-animation-iteration-count: 3; animation-iteration-count: 3; }
 .a-4s-ns { -webkit-animation-iteration-count: 4; animation-iteration-count: 4; }
 .a-5s-ns { -webkit-animation-iteration-count: 5; animation-iteration-count: 5; }
 .a-10s-ns { -webkit-animation-iteration-count: 10; animation-iteration-count: 10; }
 .a-paused-ns { -webkit-animation-play-state: paused; animation-play-state: paused; }
 .a-running-ns { -webkit-animation-play-state: running; animation-play-state: running; }
 .a-fill-none-ns { -webkit-animation-fill-mode: none; animation-fill-mode: none; }
 .a-fill-forwards-ns { -webkit-animation-fill-mode: forwards; animation-fill-mode: forwards; }
 .a-fill-backwards-ns { -webkit-animation-fill-mode: backwards; animation-fill-mode: backwards; }
 .a-fill-both-ns { -webkit-animation-fill-mode: both; animation-fill-mode: both; }
 .a-delay-vf-ns { -webkit-animation-delay: .25s; animation-delay: .25s; }
 .a-delay-f-ns { -webkit-animation-delay: .5s; animation-delay: .5s; }
 .a-delay-n-ns { -webkit-animation-delay: 1s; animation-delay: 1s; }
 .a-delay-s-ns { -webkit-animation-delay: 2s; animation-delay: 2s; }
 .a-delay-vs-ns { -webkit-animation-delay: 2.5s; animation-delay: 2.5s; }
 .a--zoom-in-out-ns { -webkit-animation-name: zoom-in-out; animation-name: zoom-in-out; }
 .a--zoom-out-in-ns { -webkit-animation-name: zoom-out-in; animation-name: zoom-out-in; }
 .a--fade-in-ns { -webkit-animation-name: fade-in; animation-name: fade-in; }
 .a--fade-out-ns { -webkit-animation-name: fade-out; animation-name: fade-out; }
 .a--fade-in-out-ns { -webkit-animation-name: fade-in-out; animation-name: fade-in-out; }
 .a--fade-out-in-ns { -webkit-animation-name: fade-out-in; animation-name: fade-out-in; }
 .a--slide-to-top-ns { -webkit-animation-name: slide-to-top; animation-name: slide-to-top; }
 .a--slide-to-right-ns { -webkit-animation-name: slide-to-right; animation-name: slide-to-right; }
 .a--slide-to-bottom-ns { -webkit-animation-name: slide-to-bottom; animation-name: slide-to-bottom; }
 .a--slide-to-left-ns { -webkit-animation-name: slide-to-left; animation-name: slide-to-left; }
 .a--slide-toggle-top-ns { -webkit-animation-name: slide-toggle-top; animation-name: slide-toggle-top; }
 .a--slide-toggle-right-ns { -webkit-animation-name: slide-toggle-right; animation-name: slide-toggle-right; }
 .a--slide-toggle-bottom-ns { -webkit-animation-name: slide-toggle-bottom; animation-name: slide-toggle-bottom; }
 .a--slide-toggle-left-ns { -webkit-animation-name: slide-toggle-left; animation-name: slide-toggle-left; }
 .a--shake-ns { -webkit-animation-name: shake; animation-name: shake; }
 .a--wobble-ns { -webkit-animation-name: wobble; animation-name: wobble; }
 .a--rotate-ns { -webkit-animation-name: rotate; animation-name: rotate; }
 .a--tilt-right-ns { -webkit-animation-name: tilt-right; animation-name: tilt-right; }
 .a--tilt-left-ns { -webkit-animation-name: tilt-left; animation-name: tilt-left; }
 .a-none-ns { -webkit-animation: none; animation: none; }
}
@media screen and (min-width: 30em) and (max-width: 60em) {
 .a-zoom-in-out-m { -webkit-animation: zoom-in-out 1s ease, fade-in 1s ease; animation: zoom-in-out 1s ease, fade-in 1s ease; }
 .a-zoom-out-in-m { -webkit-animation: zoom-out-in 1s ease, fade-in 1s ease; animation: zoom-out-in 1s ease, fade-in 1s ease; }
 .a-fade-in-m { -webkit-animation: fade-in 1s ease; animation: fade-in 1s ease; }
 .a-fade-out-m { -webkit-animation: fade-out 1s ease; animation: fade-out 1s ease; }
 .a-fade-in-out-m { -webkit-animation: fade-in-out 1s ease; animation: fade-in-out 1s ease; }
 .a-fade-out-in-m { -webkit-animation: fade-out-in 1s ease; animation: fade-out-in 1s ease; }
 .a-slide-to-top-m { -webkit-animation: slide-to-top 1s ease, fade-in 1s ease; animation: slide-to-top 1s ease, fade-in 1s ease; }
 .a-slide-to-right-m { -webkit-animation: slide-to-right 1s ease, fade-in 1s ease; animation: slide-to-right 1s ease, fade-in 1s ease; }
 .a-slide-to-bottom-m { -webkit-animation: slide-to-bottom 1s ease, fade-in 1s ease; animation: slide-to-bottom 1s ease, fade-in 1s ease; }
 .a-slide-to-left-m { -webkit-animation: slide-to-left 1s ease, fade-in 1s ease; animation: slide-to-left 1s ease, fade-in 1s ease; }
 .a-slide-toggle-top-m { -webkit-animation: slide-toggle-top 1s ease, fade-in 1s ease; animation: slide-toggle-top 1s ease, fade-in 1s ease; }
 .a-slide-toggle-right-m { -webkit-animation: slide-toggle-right 1s ease, fade-in 1s ease; animation: slide-toggle-right 1s ease, fade-in 1s ease; }
 .a-slide-toggle-bottom-m { -webkit-animation: slide-toggle-bottom 1s ease, fade-in 1s ease; animation: slide-toggle-bottom 1s ease, fade-in 1s ease; }
 .a-slide-toggle-right-m { -webkit-animation: slide-toggle-right 1s ease, fade-in 1s ease; animation: slide-toggle-right 1s ease, fade-in 1s ease; }
 .a-shake-m { -webkit-animation: shake 1s ease, fade-in 1s ease; animation: shake 1s ease, fade-in 1s ease; }
 .a-wobble-m { -webkit-animation: wobble 1s ease, fade-in 1s ease; animation: wobble 1s ease, fade-in 1s ease; }
 .a-rotate-m { -webkit-animation: rotate 1s ease, fade-in 1s ease; animation: rotate 1s ease, fade-in 1s ease; }
 .a-tilt-right-m { -webkit-animation: tilt-right 1s ease, fade-in 1s ease; animation: tilt-right 1s ease, fade-in 1s ease; }
 .a-tilt-left-m { -webkit-animation: tilt-left 1s ease, fade-in 1s ease; animation: tilt-left 1s ease, fade-in 1s ease; }
 .a-restart-m.e-tigger, .a-restart-m.e-active:active, .a-restart-m.e-hover:hover { -webkit-animation-name: none; animation-name: none; }
 .a-vf-m { -webkit-animation-duration: .25s; animation-duration: .25s; }
 .a-f-m { -webkit-animation-duration: .5s; animation-duration: .5s; }
 .a-n-m { -webkit-animation-duration: 1s; animation-duration: 1s; }
 .a-s-m { -webkit-animation-duration: 2s; animation-duration: 2s; }
 .a-vs-m { -webkit-animation-duration: 2.5s; animation-duration: 2.5s; }
 .a-bs-m { -webkit-animation-duration: 3s; animation-duration: 3s; }
 .a-ss-m { -webkit-animation-duration: 5s; animation-duration: 5s; }
 .a-normal-m { -webkit-animation-direction: normal; animation-direction: normal; }
 .a-reverse-m { -webkit-animation-direction: reverse; animation-direction: reverse; }
 .a-alternate-m { -webkit-animation-direction: alternate; animation-direction: alternate; }
 .a-alternate-reverse-m { -webkit-animation-direction: alternate-reverse; animation-direction: alternate-reverse; }
 .a-ease-m { -webkit-animation-timing-function: ease; animation-timing-function: ease; }
 .a-ease-in-m { -webkit-animation-timing-function: ease-in; animation-timing-function: ease-in; }
 .a-ease-out-m { -webkit-animation-timing-function: ease-out; animation-timing-function: ease-out; }
 .a-ease-in-out-m { -webkit-animation-timing-function: ease-in-out; animation-timing-function: ease-in-out; }
 .a-linear-m { -webkit-animation-timing-function: linear; animation-timing-function: linear; }
 .a-step-start-m { -webkit-animation-timing-function: step-start; animation-timing-function: step-start; }
 .a-step-end-m { -webkit-animation-timing-function: step-end; animation-timing-function: step-end; }
 .a-infinite-m { -webkit-animation-iteration-count: infinite; animation-iteration-count: infinite; }
 .a-2s-m { -webkit-animation-iteration-count: 2; animation-iteration-count: 2; }
 .a-3s-m { -webkit-animation-iteration-count: 3; animation-iteration-count: 3; }
 .a-4s-m { -webkit-animation-iteration-count: 4; animation-iteration-count: 4; }
 .a-5s-m { -webkit-animation-iteration-count: 5; animation-iteration-count: 5; }
 .a-10s-m { -webkit-animation-iteration-count: 10; animation-iteration-count: 10; }
 .a-paused-m { -webkit-animation-play-state: paused; animation-play-state: paused; }
 .a-running-m { -webkit-animation-play-state: running; animation-play-state: running; }
 .a-fill-none-m { -webkit-animation-fill-mode: none; animation-fill-mode: none; }
 .a-fill-forwards-m { -webkit-animation-fill-mode: forwards; animation-fill-mode: forwards; }
 .a-fill-backwards-m { -webkit-animation-fill-mode: backwards; animation-fill-mode: backwards; }
 .a-fill-both-m { -webkit-animation-fill-mode: both; animation-fill-mode: both; }
 .a-delay-vf-m { -webkit-animation-delay: .25s; animation-delay: .25s; }
 .a-delay-f-m { -webkit-animation-delay: .5s; animation-delay: .5s; }
 .a-delay-n-m { -webkit-animation-delay: 1s; animation-delay: 1s; }
 .a-delay-s-m { -webkit-animation-delay: 2s; animation-delay: 2s; }
 .a-delay-vs-m { -webkit-animation-delay: 2.5s; animation-delay: 2.5s; }
 .a--zoom-in-out-m { -webkit-animation-name: zoom-in-out; animation-name: zoom-in-out; }
 .a--zoom-out-in-m { -webkit-animation-name: zoom-out-in; animation-name: zoom-out-in; }
 .a--fade-in-m { -webkit-animation-name: fade-in; animation-name: fade-in; }
 .a--fade-out-m { -webkit-animation-name: fade-out; animation-name: fade-out; }
 .a--fade-in-out-m { -webkit-animation-name: fade-in-out; animation-name: fade-in-out; }
 .a--fade-out-in-m { -webkit-animation-name: fade-out-in; animation-name: fade-out-in; }
 .a--slide-to-top-m { -webkit-animation-name: slide-to-top; animation-name: slide-to-top; }
 .a--slide-to-right-m { -webkit-animation-name: slide-to-right; animation-name: slide-to-right; }
 .a--slide-to-bottom-m { -webkit-animation-name: slide-to-bottom; animation-name: slide-to-bottom; }
 .a--slide-to-left-m { -webkit-animation-name: slide-to-left; animation-name: slide-to-left; }
 .a--slide-toggle-top-m { -webkit-animation-name: slide-toggle-top; animation-name: slide-toggle-top; }
 .a--slide-toggle-right-m { -webkit-animation-name: slide-toggle-right; animation-name: slide-toggle-right; }
 .a--slide-toggle-bottom-m { -webkit-animation-name: slide-toggle-bottom; animation-name: slide-toggle-bottom; }
 .a--slide-toggle-left-m { -webkit-animation-name: slide-toggle-left; animation-name: slide-toggle-left; }
 .a--shake-m { -webkit-animation-name: shake; animation-name: shake; }
 .a--wobble-m { -webkit-animation-name: wobble; animation-name: wobble; }
 .a--rotate-m { -webkit-animation-name: rotate; animation-name: rotate; }
 .a--tilt-right-m { -webkit-animation-name: tilt-right; animation-name: tilt-right; }
 .a--tilt-left-m { -webkit-animation-name: tilt-left; animation-name: tilt-left; }
 .a-none-m { -webkit-animation: none; animation: none; }
}
@media screen and (max-width: 60em) and (orientation: landscape) {
 .a-zoom-in-out-ml { -webkit-animation: zoom-in-out 1s ease, fade-in 1s ease; animation: zoom-in-out 1s ease, fade-in 1s ease; }
 .a-zoom-out-in-ml { -webkit-animation: zoom-out-in 1s ease, fade-in 1s ease; animation: zoom-out-in 1s ease, fade-in 1s ease; }
 .a-fade-in-ml { -webkit-animation: fade-in 1s ease; animation: fade-in 1s ease; }
 .a-fade-out-ml { -webkit-animation: fade-out 1s ease; animation: fade-out 1s ease; }
 .a-fade-in-out-ml { -webkit-animation: fade-in-out 1s ease; animation: fade-in-out 1s ease; }
 .a-fade-out-in-ml { -webkit-animation: fade-out-in 1s ease; animation: fade-out-in 1s ease; }
 .a-slide-to-top-ml { -webkit-animation: slide-to-top 1s ease, fade-in 1s ease; animation: slide-to-top 1s ease, fade-in 1s ease; }
 .a-slide-to-right-ml { -webkit-animation: slide-to-right 1s ease, fade-in 1s ease; animation: slide-to-right 1s ease, fade-in 1s ease; }
 .a-slide-to-bottom-ml { -webkit-animation: slide-to-bottom 1s ease, fade-in 1s ease; animation: slide-to-bottom 1s ease, fade-in 1s ease; }
 .a-slide-to-left-ml { -webkit-animation: slide-to-left 1s ease, fade-in 1s ease; animation: slide-to-left 1s ease, fade-in 1s ease; }
 .a-slide-toggle-top-ml { -webkit-animation: slide-toggle-top 1s ease, fade-in 1s ease; animation: slide-toggle-top 1s ease, fade-in 1s ease; }
 .a-slide-toggle-right-ml { -webkit-animation: slide-toggle-right 1s ease, fade-in 1s ease; animation: slide-toggle-right 1s ease, fade-in 1s ease; }
 .a-slide-toggle-bottom-ml { -webkit-animation: slide-toggle-bottom 1s ease, fade-in 1s ease; animation: slide-toggle-bottom 1s ease, fade-in 1s ease; }
 .a-slide-toggle-right-ml { -webkit-animation: slide-toggle-right 1s ease, fade-in 1s ease; animation: slide-toggle-right 1s ease, fade-in 1s ease; }
 .a-shake-ml { -webkit-animation: shake 1s ease, fade-in 1s ease; animation: shake 1s ease, fade-in 1s ease; }
 .a-wobble-ml { -webkit-animation: wobble 1s ease, fade-in 1s ease; animation: wobble 1s ease, fade-in 1s ease; }
 .a-rotate-ml { -webkit-animation: rotate 1s ease, fade-in 1s ease; animation: rotate 1s ease, fade-in 1s ease; }
 .a-tilt-right-ml { -webkit-animation: tilt-right 1s ease, fade-in 1s ease; animation: tilt-right 1s ease, fade-in 1s ease; }
 .a-tilt-left-ml { -webkit-animation: tilt-left 1s ease, fade-in 1s ease; animation: tilt-left 1s ease, fade-in 1s ease; }
 .a-restart-ml.e-tigger, .a-restart-ml.e-active:active,
 .a-restart-ml.e-hover:hover { -webkit-animation-name: none; animation-name: none; }
 .a-vf-ml { -webkit-animation-duration: .25s; animation-duration: .25s; }
 .a-f-ml { -webkit-animation-duration: .5s; animation-duration: .5s; }
 .a-n-ml { -webkit-animation-duration: 1s; animation-duration: 1s; }
 .a-s-ml { -webkit-animation-duration: 2s; animation-duration: 2s; }
 .a-vs-ml { -webkit-animation-duration: 2.5s; animation-duration: 2.5s; }
 .a-bs-ml { -webkit-animation-duration: 3s; animation-duration: 3s; }
 .a-ss-ml { -webkit-animation-duration: 5s; animation-duration: 5s; }
 .a-normal-ml { -webkit-animation-direction: normal; animation-direction: normal; }
 .a-reverse-ml { -webkit-animation-direction: reverse; animation-direction: reverse; }
 .a-alternate-ml { -webkit-animation-direction: alternate; animation-direction: alternate; }
 .a-alternate-reverse-ml { -webkit-animation-direction: alternate-reverse; animation-direction: alternate-reverse; }
 .a-ease-ml { -webkit-animation-timing-function: ease; animation-timing-function: ease; }
 .a-ease-in-ml { -webkit-animation-timing-function: ease-in; animation-timing-function: ease-in; }
 .a-ease-out-ml { -webkit-animation-timing-function: ease-out; animation-timing-function: ease-out; }
 .a-ease-in-out-ml { -webkit-animation-timing-function: ease-in-out; animation-timing-function: ease-in-out; }
 .a-linear-ml { -webkit-animation-timing-function: linear; animation-timing-function: linear; }
 .a-step-start-ml { -webkit-animation-timing-function: step-start; animation-timing-function: step-start; }
 .a-step-end-ml { -webkit-animation-timing-function: step-end; animation-timing-function: step-end; }
 .a-infinite-ml { -webkit-animation-iteration-count: infinite; animation-iteration-count: infinite; }
 .a-2s-ml { -webkit-animation-iteration-count: 2; animation-iteration-count: 2; }
 .a-3s-ml { -webkit-animation-iteration-count: 3; animation-iteration-count: 3; }
 .a-4s-ml { -webkit-animation-iteration-count: 4; animation-iteration-count: 4; }
 .a-5s-ml { -webkit-animation-iteration-count: 5; animation-iteration-count: 5; }
 .a-10s-ml { -webkit-animation-iteration-count: 10; animation-iteration-count: 10; }
 .a-paused-ml { -webkit-animation-play-state: paused; animation-play-state: paused; }
 .a-running-ml { -webkit-animation-play-state: running; animation-play-state: running; }
 .a-fill-none-ml { -webkit-animation-fill-mode: none; animation-fill-mode: none; }
 .a-fill-forwards-ml { -webkit-animation-fill-mode: forwards; animation-fill-mode: forwards; }
 .a-fill-backwards-ml { -webkit-animation-fill-mode: backwards; animation-fill-mode: backwards; }
 .a-fill-both-ml { -webkit-animation-fill-mode: both; animation-fill-mode: both; }
 .a-delay-vf-ml { -webkit-animation-delay: .25s; animation-delay: .25s; }
 .a-delay-f-ml { -webkit-animation-delay: .5s; animation-delay: .5s; }
 .a-delay-n-ml { -webkit-animation-delay: 1s; animation-delay: 1s; }
 .a-delay-s-ml { -webkit-animation-delay: 2s; animation-delay: 2s; }
 .a-delay-vs-ml { -webkit-animation-delay: 2.5s; animation-delay: 2.5s; }
 .a--zoom-in-out-ml { -webkit-animation-name: zoom-in-out; animation-name: zoom-in-out; }
 .a--zoom-out-in-ml { -webkit-animation-name: zoom-out-in; animation-name: zoom-out-in; }
 .a--fade-in-ml { -webkit-animation-name: fade-in; animation-name: fade-in; }
 .a--fade-out-ml { -webkit-animation-name: fade-out; animation-name: fade-out; }
 .a--fade-in-out-ml { -webkit-animation-name: fade-in-out; animation-name: fade-in-out; }
 .a--fade-out-in-ml { -webkit-animation-name: fade-out-in; animation-name: fade-out-in; }
 .a--slide-to-top-ml { -webkit-animation-name: slide-to-top; animation-name: slide-to-top; }
 .a--slide-to-right-ml { -webkit-animation-name: slide-to-right; animation-name: slide-to-right; }
 .a--slide-to-bottom-ml { -webkit-animation-name: slide-to-bottom; animation-name: slide-to-bottom; }
 .a--slide-to-left-ml { -webkit-animation-name: slide-to-left; animation-name: slide-to-left; }
 .a--slide-toggle-top-ml { -webkit-animation-name: slide-toggle-top; animation-name: slide-toggle-top; }
 .a--slide-toggle-right-ml { -webkit-animation-name: slide-toggle-right; animation-name: slide-toggle-right; }
 .a--slide-toggle-bottom-ml { -webkit-animation-name: slide-toggle-bottom; animation-name: slide-toggle-bottom; }
 .a--slide-toggle-left-ml { -webkit-animation-name: slide-toggle-left; animation-name: slide-toggle-left; }
 .a--shake-ml { -webkit-animation-name: shake; animation-name: shake; }
 .a--wobble-ml { -webkit-animation-name: wobble; animation-name: wobble; }
 .a--rotate-ml { -webkit-animation-name: rotate; animation-name: rotate; }
 .a--tilt-right-ml { -webkit-animation-name: tilt-right; animation-name: tilt-right; }
 .a--tilt-left-ml { -webkit-animation-name: tilt-left; animation-name: tilt-left; }
 .a-none-ml { -webkit-animation: none; animation: none; }
}
@media screen and (min-width: 60em) {
 .a-zoom-in-out-l { -webkit-animation: zoom-in-out 1s ease, fade-in 1s ease; animation: zoom-in-out 1s ease, fade-in 1s ease; }
 .a-zoom-out-in-l { -webkit-animation: zoom-out-in 1s ease, fade-in 1s ease; animation: zoom-out-in 1s ease, fade-in 1s ease; }
 .a-fade-in-l { -webkit-animation: fade-in 1s ease; animation: fade-in 1s ease; }
 .a-fade-out-l { -webkit-animation: fade-out 1s ease; animation: fade-out 1s ease; }
 .a-fade-in-out-l { -webkit-animation: fade-in-out 1s ease; animation: fade-in-out 1s ease; }
 .a-fade-out-in-l { -webkit-animation: fade-out-in 1s ease; animation: fade-out-in 1s ease; }
 .a-slide-to-top-l { -webkit-animation: slide-to-top 1s ease, fade-in 1s ease; animation: slide-to-top 1s ease, fade-in 1s ease; }
 .a-slide-to-right-l { -webkit-animation: slide-to-right 1s ease, fade-in 1s ease; animation: slide-to-right 1s ease, fade-in 1s ease; }
 .a-slide-to-bottom-l { -webkit-animation: slide-to-bottom 1s ease, fade-in 1s ease; animation: slide-to-bottom 1s ease, fade-in 1s ease; }
 .a-slide-to-left-l { -webkit-animation: slide-to-left 1s ease, fade-in 1s ease; animation: slide-to-left 1s ease, fade-in 1s ease; }
 .a-slide-toggle-top-l { -webkit-animation: slide-toggle-top 1s ease, fade-in 1s ease; animation: slide-toggle-top 1s ease, fade-in 1s ease; }
 .a-slide-toggle-right-l { -webkit-animation: slide-toggle-right 1s ease, fade-in 1s ease; animation: slide-toggle-right 1s ease, fade-in 1s ease; }
 .a-slide-toggle-bottom-l { -webkit-animation: slide-toggle-bottom 1s ease, fade-in 1s ease; animation: slide-toggle-bottom 1s ease, fade-in 1s ease; }
 .a-slide-toggle-right-l { -webkit-animation: slide-toggle-right 1s ease, fade-in 1s ease; animation: slide-toggle-right 1s ease, fade-in 1s ease; }
 .a-shake-l { -webkit-animation: shake 1s ease, fade-in 1s ease; animation: shake 1s ease, fade-in 1s ease; }
 .a-wobble-l { -webkit-animation: wobble 1s ease, fade-in 1s ease; animation: wobble 1s ease, fade-in 1s ease; }
 .a-rotate-l { -webkit-animation: rotate 1s ease, fade-in 1s ease; animation: rotate 1s ease, fade-in 1s ease; }
 .a-tilt-right-l { -webkit-animation: tilt-right 1s ease, fade-in 1s ease; animation: tilt-right 1s ease, fade-in 1s ease; }
 .a-tilt-left-l { -webkit-animation: tilt-left 1s ease, fade-in 1s ease; animation: tilt-left 1s ease, fade-in 1s ease; }
 .a-restart-l.e-tigger, .a-restart-l.e-active:active, .a-restart-l.e-hover:hover { -webkit-animation-name: none; animation-name: none; }
 .a-vf-l { -webkit-animation-duration: .25s; animation-duration: .25s; }
 .a-f-l { -webkit-animation-duration: .5s; animation-duration: .5s; }
 .a-n-l { -webkit-animation-duration: 1s; animation-duration: 1s; }
 .a-s-l { -webkit-animation-duration: 2s; animation-duration: 2s; }
 .a-vs-l { -webkit-animation-duration: 2.5s; animation-duration: 2.5s; }
 .a-bs-l { -webkit-animation-duration: 3s; animation-duration: 3s; }
 .a-ss-l { -webkit-animation-duration: 5s; animation-duration: 5s; }
 .a-normal-l { -webkit-animation-direction: normal; animation-direction: normal; }
 .a-reverse-l { -webkit-animation-direction: reverse; animation-direction: reverse; }
 .a-alternate-l { -webkit-animation-direction: alternate; animation-direction: alternate; }
 .a-alternate-reverse-l { -webkit-animation-direction: alternate-reverse; animation-direction: alternate-reverse; }
 .a-ease-l { -webkit-animation-timing-function: ease; animation-timing-function: ease; }
 .a-ease-in-l { -webkit-animation-timing-function: ease-in; animation-timing-function: ease-in; }
 .a-ease-out-l { -webkit-animation-timing-function: ease-out; animation-timing-function: ease-out; }
 .a-ease-in-out-l { -webkit-animation-timing-function: ease-in-out; animation-timing-function: ease-in-out; }
 .a-linear-l { -webkit-animation-timing-function: linear; animation-timing-function: linear; }
 .a-step-start-l { -webkit-animation-timing-function: step-start; animation-timing-function: step-start; }
 .a-step-end-l { -webkit-animation-timing-function: step-end; animation-timing-function: step-end; }
 .a-infinite-l { -webkit-animation-iteration-count: infinite; animation-iteration-count: infinite; }
 .a-2s-l { -webkit-animation-iteration-count: 2; animation-iteration-count: 2; }
 .a-3s-l { -webkit-animation-iteration-count: 3; animation-iteration-count: 3; }
 .a-4s-l { -webkit-animation-iteration-count: 4; animation-iteration-count: 4; }
 .a-5s-l { -webkit-animation-iteration-count: 5; animation-iteration-count: 5; }
 .a-10s-l { -webkit-animation-iteration-count: 10; animation-iteration-count: 10; }
 .a-paused-l { -webkit-animation-play-state: paused; animation-play-state: paused; }
 .a-running-l { -webkit-animation-play-state: running; animation-play-state: running; }
 .a-fill-none-l { -webkit-animation-fill-mode: none; animation-fill-mode: none; }
 .a-fill-forwards-l { -webkit-animation-fill-mode: forwards; animation-fill-mode: forwards; }
 .a-fill-backwards-l { -webkit-animation-fill-mode: backwards; animation-fill-mode: backwards; }
 .a-fill-both-l { -webkit-animation-fill-mode: both; animation-fill-mode: both; }
 .a-delay-vf-l { -webkit-animation-delay: .25s; animation-delay: .25s; }
 .a-delay-f-l { -webkit-animation-delay: .5s; animation-delay: .5s; }
 .a-delay-n-l { -webkit-animation-delay: 1s; animation-delay: 1s; }
 .a-delay-s-l { -webkit-animation-delay: 2s; animation-delay: 2s; }
 .a-delay-vs-l { -webkit-animation-delay: 2.5s; animation-delay: 2.5s; }
 .a--zoom-in-out-l { -webkit-animation-name: zoom-in-out; animation-name: zoom-in-out; }
 .a--zoom-out-in-l { -webkit-animation-name: zoom-out-in; animation-name: zoom-out-in; }
 .a--fade-in-l { -webkit-animation-name: fade-in; animation-name: fade-in; }
 .a--fade-out-l { -webkit-animation-name: fade-out; animation-name: fade-out; }
 .a--fade-in-out-l { -webkit-animation-name: fade-in-out; animation-name: fade-in-out; }
 .a--fade-out-in-l { -webkit-animation-name: fade-out-in; animation-name: fade-out-in; }
 .a--slide-to-top-l { -webkit-animation-name: slide-to-top; animation-name: slide-to-top; }
 .a--slide-to-right-l { -webkit-animation-name: slide-to-right; animation-name: slide-to-right; }
 .a--slide-to-bottom-l { -webkit-animation-name: slide-to-bottom; animation-name: slide-to-bottom; }
 .a--slide-to-left-l { -webkit-animation-name: slide-to-left; animation-name: slide-to-left; }
 .a--slide-toggle-top-l { -webkit-animation-name: slide-toggle-top; animation-name: slide-toggle-top; }
 .a--slide-toggle-right-l { -webkit-animation-name: slide-toggle-right; animation-name: slide-toggle-right; }
 .a--slide-toggle-bottom-l { -webkit-animation-name: slide-toggle-bottom; animation-name: slide-toggle-bottom; }
 .a--slide-toggle-left-l { -webkit-animation-name: slide-toggle-left; animation-name: slide-toggle-left; }
 .a--shake-l { -webkit-animation-name: shake; animation-name: shake; }
 .a--wobble-l { -webkit-animation-name: wobble; animation-name: wobble; }
 .a--rotate-l { -webkit-animation-name: rotate; animation-name: rotate; }
 .a--tilt-right-l { -webkit-animation-name: tilt-right; animation-name: tilt-right; }
 .a--tilt-left-l { -webkit-animation-name: tilt-left; animation-name: tilt-left; }
 .a-none-l { -webkit-animation: none; animation: none; }
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

