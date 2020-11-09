# Wirez
Wirez is a starter file for wireframe design systems.

It combines a strict, grid-based structure with a brutalist aesthetic to help you create professional yet unmistakably disposable wireframe designs.

What you get: an 8-point layout grid, basic fills and type styles, along with a set of geometric icons and input controls. Use them as the building blocks for your own wireframe design system.

## Getting started

To get started duplicate the Wirez Kit file available on [Figma Community](https://www.figma.com/community/file/822440764002706075/Wirez). 

## Layout

Includes frames for the following viewport widths:

* 360px
* 768px
* 1280px
* 1440px

Frames are configured with an 8-point layout grid and a 4-point baseline grid:

* 360px
  * columns: 4 @ 60px
  * margins: 24px
  * gutters: 24px
* 768px
  * columns: 8 @ 76px
  * margins: 24px
  * gutters: 16px
* 1280px
  * columns: 12 @ 88px
  * margins: 24px
  * gutters: 16px
* 1440px
  * columns: 12 @ 80px
  * margins: 64px
  * gutters: 32px

## Colors

Includes five shades of gray + white used as default background fills as well as four basic hues (red, blue, green, and yellow) for additional contrast and visibility.

```
$hue-red: #FF0000;
$hue-green: #008000;
$hue-blue: #0000FF;
$hue-yellow: #FFFF00;
$gray-00: #FFFFFF;
$gray-10: #EEEEEE;
$gray-20: #BDBDBD;
$gray-60: #757575;
$gray-80: #424242;
$gray-90: #212121;
```

## Typography

Base font size set to 16px, line height of 1.5 and scale factor of 1.618.

```
body {
  font-family: Menlo, Fira Code, monospace;
  font-size: 16px;
  line-height: 24px;
}

h1 {
  font-size: 68px;
  line-height: 72px;
  margin-top: 24px;
  margin-bottom: 48px;
}

h2 {
  font-size: 42px;
  line-height: 48px;
  margin-top: 24px;
  margin-bottom: 24px;
}

h3 {
  font-size: 26px;
  line-height: 48px;
  margin-top: 24px;
  margin-bottom: 0px;
}

h4 {
  font-size: 16px;
  line-height: 24px;
  margin-top: 24px;
  margin-bottom: 0px;
  text-transform: uppercase;
}
```
## License

Wirez is available under [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/). Please link back to the source when you share and / or adapt any of the contents.
