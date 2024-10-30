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