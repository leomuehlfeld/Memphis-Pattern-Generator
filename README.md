# Memphis-Pattern-Generator
![license](https://badgen.net/badge/license/MIT/blue)
Simple Paper.js pattern generator
[Try It!](https://pattern.leomuehlfeld.at)

![screen](https://user-images.githubusercontent.com/22169889/28363860-69097bda-6c82-11e7-992f-95fa65e79fc5.jpg)

## Motivation
After working on a project which required patterns in the style of those created by the Memphis Group, I thougth it would be an interesting challenge to come up with a randomizer for those graphics.
I chose "paper.js" and wrote a minimal page with two buttons. One is for a random pattern which you can download as an SVG by clicking the other.
Value Sliders might be included when I find some time.

## Manipulate Variables
At the moment, this generator does not have any user input options except manipulating the source. Sliders might be implemented in the Future. Until then this is what you can change:

### Size
```javascript
const size = 15;
```
### Colors
```javascript  
const red = '#f44e45';
const blue = '#4f4faf';
const yellow = '#f4d65b';
const green = '#afe8b4';
const coral = '#ffe8bb';
const strokecolor = '#000';
```

### Grid Spacings
```javascript
const randommin = 30;
const randommax = 80;

var xspacing = 170;
var yspacing = 170;
```
* Randommin/max defines the lower and upper limits for the randomizer.
* x/yspacing defines the spacing between grid points on each axis.

## Authors
This Generator was written by [Leo Mühlfeld](https://leomuehlfeld.at). It uses [Paper.js](https://github.com/paperjs/paper.js) and was inspired by the awesome work of the Memphis Group.
