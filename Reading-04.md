# Chapter 5: “Images” (pp.94-125)

**stock images** - These are copy write images you pay to use.

**alt text** - The text used in the alt attribute. It should give an accurate description of the image content so it can be understood by screen reader software.

**bitmap** - A type of image format known as PGs, GIFs, and PNGs.

**resolution** - The number of squares that fit within a 1-inch x 1-inch square area of an image.

**pixels** - Images appearing on computer screens are made of tiny square
**vectors** -  Images created by placing points on a grid, and drawing lines between those points. A color can then be added to "fill in" the lines that have been created.

The <img> element is used to add images to a web page.
You must always specify a src attribute to indicate the source of an image and an alt attribute to describe the content of an image.
You should save images at the size you will be using them on the web page and in the appropriate format.
Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.

# Chapter 11: “Color” (pp.246-263)

**Background  color** - A property that sets the color of the background for that box

**Foreground color** - The color property allows you to specify the color of text inside an element.

You can specify any color in CSS in one of three ways:

**RGB values**: These express colors in terms of how much red, green and blue are used to make it up. For ex. RGB(100,100,90)

**Hex Codes**: These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. ex. #ee3e80

**Color names**: 147 predefined color names are recognized
by browsers. For example: DarkCyan

**Hue** - Near to the colloquial idea of color. Technically speaking, however, color can also have saturation and brightness as well as hue.

**Saturation** - The amount of gray in a color. At maximum saturation, there would be no gray in the color. At minimum saturation, the color would be mostly gray.

**Brightness** - a "value" referring to how much black is in a color. At maximum brightness, there would be no black in the color. At minimum brightness, the color would be very dark.

Color not only brings your site to life but also helps convey the mood and evokes reactions.

There are three ways to specify colors in CSS: RGB values, hex codes, and color names.
Color pickers can help you find the color you want.
It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content).
CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.

CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as HSLA
# Chapter 12: “Text” (pp.264-299)

**Takeaways**:

If you design on a Mac, it is important to check what the typefaces look like on a PC because PCs can render type less smoothly. But if you design on a PC, then it should look fine on a Mac.
 
Different browsers support different formats for fonts (in the same way that they support different audio and video formats), so you will need to supply the font in several variations to reach all browsers.
 
**font-family** - The property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies.

**font-size** - The property enables you to specify a size for the font. There are several ways to specify the size of a font. The most common are:

**pixels** - Pixels are commonly used because they allow web designers very precise control over how much space their text takes up. The number of pixels is followed by
the letters px.

**percentages** - The default size of the text in browsers is 16px. So size of 75% would be the equivalent of 12px, and 200% would be 32px.

**ems** - An em is equivalent to the width of a letter m.

**@font-face**- Allows you to use a font, even if it is not installed on the computer of the person browsing, by allowing you to specify a path to a copy of the font, which will be downloaded if it is not on the user's machine.

**text-transform** - The property is used to change the case of text giving it one of the following values:

**uppercase** - This causes the text to appear uppercase.

**lowercase** - This causes the text to appear lowercase.

**capitalize** - This causes the text to appear capitalized.

**text-decoration** - The property allows you to specify the following values:

**none** - This removes any decoration already applied to the text.

**underline** - This adds a line underneath the text.

**over-line** - This adds a line over the top of the text.

**line-through** - This adds a line through words.

**blink** - This animates the text to make it flash on and off.

**leading** - (pronounced ledding) is a term typographers use for the vertical space between lines of text.

**descender** - The part of a letter that drops beneath the baseline.

**ascender** - The highest point of a letter

**Kerning** - The term typographers use for the space between each letter. You can control the space between each letter with the letter-spacing property.

The text-align property allows you to control the alignment of text. The property can take one of four values:

**left** - This indicates that the text should be left-aligned.

**right** - This indicates that the text should be right-aligned.

**center** - This allows you to center text.

**justify** - This indicates that every line in a paragraph, except the last line, should be set to take up the full width of the containing box.

**vertical-align** - The property is a common source of confusion. It is not intended to allow you to vertically align text in the middle of block-level elements such as <p> and <div>, although it does have this effect when used with table cells (the <td> and <th> elements).

**text-indent** - The property allows you to indent the first line of text within an element. The amount you want the line indented by can be specified in a number of ways but is usually given in pixels or ems.

**text-shadow** - The property has become commonly used despite lacking support in all browsers. It is used to create a drop shadow, which is a dark version of the word just behind it and slightly offset. It can also be used to create an embossed effect by adding a shadow that is slightly lighter than the text.

There are properties to control the choice of font, size, weight, style, and spacing.
There is a limited choice of fonts that you can assume most people will have installed.

If you want to use a wider range of typefaces there are several options, but you need to have the right license to use them. You can control the space between lines of text, individual letters, and words. Text can also be aligned to the left, right, center, or justified. It can also be indented.

You can use pseudo-classes to change the style of an element when a user hovers over or clicks on text, or when they have visited a link.