# Class05

[Return to home page](https://momansi96.github.io/reading-notes/). 

## Images: 

#### Choosing Images for Your Site: 

A picture can say a thousand words, and great images help make the difference between an average-looking site and a really engaging one, Images can be used to set the tone for a site in less time than it takes to read a description. If you do not have photographs to use on your website, there are companies who sell stock images. 

* Images should: 

1. Be relevant. 
2. Convey information. 
3. Convey the right mood. 
4. Be instantly recognisable. 
5. Fit the color palette. 

* Storing Images on Your Site: If you are building a site from scratch, it is good practice to create a folder for all of the images the site uses, As a website grows, keeping images in a separate folder helps you understand how the site is organized. 

#### Adding Images: 

* "<img>": To add an image into the page you need to use an "<img>" element. This is an empty element (which means there is no closing tag). It must carry the following two attributes:
 
 1. src: This tells the browser where it can find the image file. This will usually be a relative URL pointing to an image on your own site. (Here you can see that the images are in a child folder called images). 
 2. alt: This provides a text description of the image which describes the image if you cannot see it.
 
* Height & Width of Images: You will also often see an "<img>" element use two other attributes that specify its size:
 
 1. height: This specifies the height of the image in pixels.
 2. width: This specifies the width of the image in pixels. 

* Where to Place Images in Your Code: Where an image is placed in the code will affect how it is displayed. Here are three examples of image placement that produce different results:

 1. before a paragraph: The paragraph starts on a new line after the image.
 2. inside the start of a paragraph The first row of text aligns with the bottom of the image.
 3. in the middle of a paragraph The image is placed between the words of the paragraph that it appears in.

* Three Rules for Creating Images: There are three rules to remember when you are creating images for your website which are summarized below: 

 1. Save images in the right format: Websites mainly use images in jpeg, gif, or png format. If you choose the wrong image format then your image might not look as sharp as it should and can make the web page slower to load. 
 2. Save images at the right size: You should save the image at the same width and height it will appear on the website.
 3. Use the correct resolution: Computer screens are made up of dots known as pixels. Images used on the web are also made up of tiny dots. Resolution refers to the number of dots per inch. 

* Image Formats: 

 1. JPEG: Whenever you have many different colors in a picture you should use a JPEG. 
 2. GIF: When a picture has an area that is filled with exactly the same color, it is known as flat color. 

* Image Dimensions: 

The images you use on your website should be saved at the same width and height that you want them to appear on the page, For example, if you have designed a page to include an image that is 300 pixels wide by 150 pixels tall, the image you use should be 300 x 150 pixels. You may need to use image editing tools to resize and crop the image. 

* Image Resolution: 

Images created for the web should be saved at a resolution of 72 ppi. The higher the resolution of the image, the larger the size of the file.

* Vector Images: 

Vector images differ from bitmap images and are resolution-independent. Vector images are commonly created in programs such as Adobe Illustrator.

* Animated GIFs: 

Animated GIFs show several frames of an image in sequence and therefore can be used to create simple animations.

* Transparency: 

Creating an image that is partially transparent (or "see-through") for the web involves selecting one of two formats:

 1. Transparent GIF: If the transparent part of the image has straight edges and it is 100% transparent (that is, not semi-opaque), you can save the image as a GIF (with the transparency option selected).
 2. PNG: If the transparent part of the image has diagonal or rounded edges or if you want a semiopaque transparency or a dropshadow, then you will need to save it as a PNG.

* Figure: "<figure>": Images often come with captions. HTML5 has introduced a new "<figure>" element to contain images and their caption so that the two are associated.

## Color: 

#### Foreground Color: 

The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:

1- RGB values: These express colors in terms of how much red, green, and blue are used to make it up. For example: rgb(100,100,90)
 
2- hex codes: These are six-digit codes that represent the amount of red, green, and blue in a color, preceded by a pound or hash #sign. For example: #ee3e80

3- color names: There are 147 predefined color names that are recognized by browsers.

#### Background Color: 

CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box, You can specify your choice of
background color in the same three ways you can specify
foreground colors, If you do not specify a background color, then the background is transparent. 

#### Contrast: 

When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible.

1- Low Contrast: Text is harder to read when there is low contrast between background and foreground colors. 

2- High Contrast: Text is easier to read when there is a higher contrast between background and foreground colors.

3- Medium Contrast: For long spans of text, reducing the contrast a little bit improves readability.

## Text: 

#### Techniques That Offer a Wider Choice of Typefaces: 
There are several ways to use fonts other than those listed. However, typefaces are subject to copyright, so the techniques you can choose from are limited by their respective licenses.

* Specifying Typefaces (font-family):

The font-family property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies. The value of this property is the name of the typeface you want to use. 

* Size of Type(font-size): 

The font-size property enables you to specify a size for the font. There are several ways to specify the size of a font. Themost common are:

 1. pixels: Pixels are commonly used because they allow web designers very precise control over how much space their text takes up.
 2. percentages: The default size of text in browsers is 16px. So a size of 75% would be the equivalent of 12px, and 200% would be 32px.

* More Font Choice (font-face): 

@font-face allows you to use a font, even if it is not installed on the computer of the person browsing, by allowing you to specify a path to a copy of the font, which will be downloaded if it is not on the user's machine. 

* Bold (font-weight): 

The font-weight property allows you to create bold text. There are two values that this property commonly takes:

 1. normal: This causes text to appear at a normal weight.
 2.bold: This causes text to appear bold.

* Italic (font-style): 

If you want to create italic text, you can use the font-style property. There are three values this property can take:

 1. normal: This causes text to appear in a normal style (as opposed to italic or oblique).
 2. italic: This causes text to appear italic.
 3. oblique: This causes text to appear oblique.

* Underline & Strike (text-decoration): 

The text-decoration property allows you to specify the following values:

 1. none: This removes any decoration already applied to the text.
 2. underline: This adds a line underneath the text.
 3. overline: This adds a line over the top of the text.
 4. line-through: This adds a line through words.
 5. blink This animates the text to make it flash on and off (however this is generally frowned upon, as it is considered rather annoying).

* Leading (line-height): 

In CSS, the line-height property sets the height of an entire line of text,Increasing the line-height makes the vertical gap between lines of text larger.

* Alignment (text-align): 

The text-align property allows you to control the alignment of text. The property can take one of four values:

 1. left: This indicates that the text should be left-aligned.
 2. right: This indicates that the text should be right-aligned.
 3. center: This allows you to center text.
 4. justify: This indicates that every line in a paragraph, except the last line, should be set to take up the full width of the containing box.

* Vertical Alignment (vertical-align): 

It is more commonly used with inline elements such as "<img>", "<em>", or "<strong>" elements. When used with these elements, it performs a task very similar to the HTML align attribute used on the "<img>" element. 

* Indenting Text (text-indent): 

The text-indent property allows you to indent the first line of text within an element. The amount you want the line
indented by can be specified in a number of ways but is usually given in pixels or ems.

* Drop Shadow (text-shadow): 

It is used to create a drop shadow, which is a dark version of the word just behind it and slightly offset. It can also be used to create an embossed effect by adding a shadow that is slightly lighter than the text.

* First Letter or Line (:first-letter, :first-line): 

You can specify different values for the first letter or first line of text inside an element using (:first-letter and
:first-line). 

* Styling Links (:link, :visited): 

Browsers tend to show links in blue with an underline by default, and they will change the color of links that have been
visited to help users know which pages they have been to.

In CSS, there are two pseudoclasses that allow you to set different styles for links that have and have not yet been visited.

 1. ":link": This allows you to set styles for links that have not yet been visited.
 2. :visited: This allows you to set styles for links that have been clicked on.

* Responding to Users (:hover, :active, :focus): 

There are three pseudo-classes that allow you to change the appearance of elements when a user is interacting with them.

 1. :hover: This is applied when a user hovers over an element with a pointing device such as a mouse. This has commonly been used to change the appearance of links and buttons when a user places their cursor over them. It is worth noting that such events do not work on devices that use touch screens.
 2. :active: This is applied when an element is being activated by a user; for example, when a button is being pressed or a link being clicked. Sometimes this is used to make a button or link feel more like it is being pressed by changing the
style or position of the element slightly.
 3. :focus: This is applied when an element has focus. Any element that you can interact with, such as a link you can click on or any form control can have focus.


## JPEG vs PNG vs GIF: 

- JPEG is a lossy compression specification that takes advantage of human perception. It can achieve compression ratios of 1:10 without any perceivable difference in quality. Beyond this, the compression artefacts become more prominent. Because JPEG compression works by averaging out colours of nearby pixels, JPEG images are best suited for photographs and paintings of natural scenes where the variations in colour and intensity are smooth. However, if an image contains text or lines, where a sharp contrast between adjacent pixels is desired to highlight the proper shape, this lossy compression technique does not yield good results.

- PNG is a lossless image format using DEFLATE compression. No data is lost during compression and no compression artefacts are introduced in the image. For this reason, a PNG image would retain higher quality than an image than JPEG and would look a lot sharper, it would also occupy more space on the disk. This makes it unsuitable for storing or transferring high-resolution digital photographs but a great choice for images with text, logos and shapes with sharp edges.

- GIF is also a lossless image format that uses LZW compression algorithm. It was favoured over PNG for simple graphics in websites in its early days because the support of PNG was still growing. Given that PNG is now supported across all major devices and that PNG compression is about 5–25% better than GIF compression, GIF images are now mainly used only if the image contains animations.

- Transparency
In a simple form, transparency indicates something that is completely invisible. Logos and icons often need to be placed on backgrounds with variable colours. Hence it is desirable, that the background of these logos and icons is made transparent so that a single image can be used over multiple background variations.
  
  - JPEG images don’t support transparency and are hence not usable for such cases.
  - PNG images support transparency. 
  - GIF images support transparency by declaring a single colour in the colour palette as transparent. 

- Colours
There is a significant difference in the number of colours that can be supported by these 3 formats.

 - JPEG images can support around 16 million colours. This is what makes them suitable for storing images of natural scenes.
 - PNG images mainly have two modes — PNG8 and PNG24. PNG8 can support upto 256 colours whereas PNG24 can handle upto 16 million colours like a JPEG image.
 - GIF images are limited to 256 colours. If index transparency is used, then one of these 256 colours is assigned as transparent and the remaining 255 are used for other colours.

- Animation
Animation, in this case, refers to any change or movement in the image. It doesn’t necessarily have to have frame rates like an animated video, but essentially a part or the entire image changes with time.

 - Of these 3 formats, only GIF supports animation. 


