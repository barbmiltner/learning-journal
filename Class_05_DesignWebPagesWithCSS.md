- [Return to Home Page](/README.md)

The following is a summary outline of what I learned from Jon Duckett's book _*HTML & CSS Design and Build Websites*_

# Chapter 10
## Introducing CSS

##### Review: block vs inline
**Block** elements start on a new line. Examples:
* `<h1>`-`<h6>`
* `<p>`
* `<div>`

**Inline** elements don't. Examples:
* `<b> <i> <em>`
* `<img>`
* `<span>`

#### Example styles
* Boxes
     * Width, height
     * Border color, width and style
     * Background color and images
     * Position in the browser window
* Text
  * Typeface (font)
  * Size
  * Color
  * Italic, bold, uppercase, lowercase, small-cap
  
* Other
  * There are ways to style lists, tables, and forms, etc.

### CSS can be placed these ways:
* __externally__ in a .css file that is linked to an .html file

  In the html file (in the head), link to the CSS style sheet: `<link rel="stylesheet" type="text/css" href="filename">`
* __internally__ in the head of an .html file between `<style text="text/css"></style>` tags, or
* __embedded__ in an html file using the _style=" "_ attribute

### CSS Selectors

Selectors are case sensitive. Class selectors begin with a period (.). ID selectors begin with a hash (#). You can select children, descendants, and siblings (both adjacent and general siblings) of elements.

CSS rules cascade; that is to say there is a heirarchy of precedence. The most specific rules take precendence. If there is a conflicting tie, the latest rule takes precedence. 

Some properties are inherited by child elements (such as font-family) but others aren't (such as background-color and border). To force inheritance use the value **inherit**.

### Note

Not all browsers display css the same. Check a site such as [crossbrowsertesting.com](https://app.crossbrowsertesting.com/login) to see how your site will render in different browsers and differenct operating systems. To get help fixing browser quirks visit quirksmode.org or positioniseverything.net 

Some special fonts may not render on the user's computer but you can list alternatives. Google fonts will work on any computer; just Google search and copy/paste the html and css code for the font you select.

# Chapter 11
## Color

Colors can be specified by RGD, Hex or color name (names are available for 147 colors). CSS3 can also use HSLA. Older browsers don't support CSS3.

If you don't specify a background color it will be transparent. On some browsers this will render as white but not always, so be intentional.

###HSLA
* **Hue**
  * This is a color "angle" on the color wheel from 0 to 360.
* **Saturation**
  * The amount of gray. 100% is no gray, 0% is all gray.
* **Luminosity** (lightness)
  * Unlike brightness which only adds black, luminosity adds both black (0%) and white (100%). 50% is the normal color.
* **Alpha** (transparency)
  * A number from 0 (opaque) to 1.0 (transparent).
  
Color pickers help select colors and even themes. Some check for accessibility such as colorblindness and readability factors such as contrast.
