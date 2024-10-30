# HTML Tutorial

1. All HTML documents must start with a document type declaration: ```<!DOCTYPE html>```

2. HTML headings are defined with the ```<h1>``` to ```<h6>``` tags. Each HTML heading has a default size. However, you can specify the size for any heading with the ```style``` attribute, using the CSS ```font-size``` property.

```html
<h1> Heading 1</h1>
<h2> Heading 2</h2>
<h3> Heading 3 </h3>
<h4> Heading 4 </h4>
<h5> Heading 5 </h5>
<h6> Heading 6 </h6>
<h1 style="font-size:60px;">CUSTOM FONT SIZE</h1>
```

3. HTML paragraphs are defined with the ```<p>``` . 
NOTE: With HTML, you cannot change the display by adding extra spaces or extra lines in your HTML code.
The browser will automatically remove any extra spaces and lines when the page is displayed.

```html
<p> Paragraph1</p>
<p> Paragraph2</p>
<p>
This paragraph
contains a lot of lines
in the source code,
but the browser
ignores it.
</p>

<p>
This paragraph
contains         a lot of spaces
in the source         code,
but the        browser
ignores it.
</p>
```

4. HTML links are defined with the ```<a>``` tag.

```html
<a href="https://github.com/BlackNinjaKR/HTML_Tutorial_withPics">This is a link</a>
```

5. HTML images are defined with the ```<img>``` tag.
The source file ```(src)```, alternative text ```(alt)```, ```width```, and ```height``` are provided as attributes.

```html
<img src="bird-thumbnail.jpg" alt="sample image" width="104" height="142">
```
```
There are two ways to specify the URL in the src attribute:
1. Absolute URL - Links to an external image that is hosted on another website.
Example: src="https://www.remove.bg/sample_images.jpg".

2. Relative URL - Links to an image that is hosted within the website.
Here, the URL does not include the domain name.

If the URL begins without a slash, it will be relative to the current page.
Example: src="bird-thumbnail.jpg".

If the URL begins with a slash, it will be relative to the domain.
Example: src="/images/bird-thumbnail.jpg".
```

6. The ```<br>``` tag defines a line break, and is an empty element without a closing tag.

```html
<p> Hi <br> This <br> Is <br> The <br> Use <br> Of <br> Break <br> Tag </p>
```
```
Note: HTML is Not Case Sensitive.
```

7. The ```style``` attribute is used to add styles to an element, such as color, font, size, and more.

```html
<p style="color:red;">This is a red paragraph.</p>
```

8. The ```lang``` attribute inside the ```<html>``` tag declares the language of the Web page. This is meant to assist search engines and browsers. Country codes can also be added to the language code in the ```lang``` attribute. So, the first two characters define the language of the HTML page, and the last two characters define the country.

```html
<html lang="en-US">
```

9. The ```title``` attribute defines some extra information about an element.
    The value of the ```title``` attribute will be displayed as a tooltip when you mouse over the element.

```html
<p title="I'm a tooltip">This is a paragraph.</p>
```

10. The ```<hr>``` tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule.

```html
<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>
<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr>
```

11. The text inside a ```<pre>``` element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks.

```html
<pre>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</pre>
```

12. Setting the style of an HTML element, can be done with the `style` attribute.

```html
<tagname style="property:value;">
```

The property is a CSS property. The value is a CSS value.

13. The CSS `background-color` property defines the background color for an HTML element.

```html
<body style="background-color:powderblue;">

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
```

14. The CSS `color` property defines the text color for an HTML element.

```html
<h1 style="color:blue;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>
```

15. The CSS ```font-family``` property defines the font to be used for an HTML element.

```html
<h1 style="font-family:verdana;">This is a heading</h1>
<p style="font-family:courier;">This is a paragraph.</p>
```

16. The CSS `font-size` property defines the text size for an HTML element.

```html
<h1 style="font-size:300%;">This is a heading</h1>
<p style="font-size:160%;">This is a paragraph.</p>
```

17. The CSS `text-align` property defines the horizontal text alignment for an HTML element.

```html
<h1 style="text-align:center;">Centered Heading</h1>
<p style="text-align:center;">Centered paragraph.</p>
```

18. Formatting elements were designed to display special types of text:
    1. `<b>` - Bold text
    2. `<strong>` - Important text
    3. `<i>` - Italic text
    4. `<em>` - Emphasized text
    5. `<mark>` - Marked text
    6. `<small>` - Smaller text
    7. `<del>` - Deleted/Strikethrough text
    8. `<ins>` - Inserted/Underlined text
    9. `<sub>` - Subscript text
    10. `<sup>` - Superscript text

```html
<b>This text is bold</b>
<strong>This text is important!</strong>
<i>This text is italic</i>
<em>This text is emphasized</em>
<small>This is some smaller text.</small>
<p>Do not forget to drink <mark>milk</mark> and <mark>workout</mark>today.</p>
<p>My favorite color is <del>blue</del> red.</p>
<p>This is <sub>subscripted</sub> text.</p>
<p>This is <sup>superscripted</sup> text.</p>
```

19. The HTML `<blockquote>` element defines a section that is quoted from another source.

```html
<p>Here is a quote from WWF's website:</p>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.
</blockquote>
```

20. The HTML `<q>` tag defines a short quotation.

```html
<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
```

21. The HTML `<abbr>` tag defines an abbreviation or an acronym, like "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM".

```html
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
```

22. The HTML `<address>` tag defines the contact information for the author/owner of a document or an article.

```html
<address>
Written by John Doe.<br>
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>
```

23. The HTML `<cite>` tag defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.).

```html
<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>
```

24. The HTML `<bdo>` tag is used to override the current text direction.

```html
<bdo dir="rtl">This text will be written from right to left</bdo>
```

25. You can add comments to your HTML source by using the following syntax.

```html
<!-- Write your comments here -->
```
Note: Comments are not displayed by the browser, but they can help document your HTML source code.

26. HTML supports 140 standard color-names and the following formats:
    1. RGB (Red, Green, Blue)
    2. HEX (Hexadecimal values)
    3. HSL (Hue, Saturation, Lightness)

27. To create a bookmark - first create the bookmark, then add a link to it.

```html
<h2 id="C4">Chapter 4</h2> <!-- Use the id attribute to create a bookmark -->
<a href="#C4">Jump to Chapter 4</a> <!-- Add a link to the bookmark, from within the same page -->
<a href="html_demo.html#C4">Jump to Chapter 4</a> <!-- Add a link to a bookmark on another page -->
```

28. The HTML `<map>` tag defines an image map. An image map is an image with clickable areas. The areas are defined with one or more `<area>` tags.

```html
<img src="image.jpg" alt="sample_image" usemap="#workmap">

<map name="workmap">
  <area shape="rect" coords="x11,y11,x12,y12" alt="location 1" href="location1.htm">
  <area shape="rect" coords="x21,y21,x22,y22" alt="location 2" href="location2.htm">
  <area shape="circle" coords="x,y,radius" alt="location 3" href="location3.htm">
</map>

<!-- rect = Rectangle -->
<!-- circle = Circle -->
<!-- poly = Polygon -->
<!-- default = Entire region -->
```
The idea behind an image map is that you should be able to perform different actions depending on where in the image you click.

To create an image map you need an image, and some HTML code that describes the clickable areas.