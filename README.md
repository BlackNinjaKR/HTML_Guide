# HTML Tutorial

1. All HTML documents must start with a document type declaration: ```<!DOCTYPE html>```

2. HTML headings are defined with the ```<h1>``` to ```<h6>``` tags.

```html
<h1> Heading 1</h1>
<h2> Heading 2</h2>
<h3> Heading 3 </h3>
<h4> Heading 4 </h4>
<h5> Heading 5 </h5>
<h6> Heading 6 </h6>
```

3. HTML paragraphs are defined with the ```<p>``` tag

```html
<p> Paragraph1</p>
<p> Paragraph2</p>
```

4. HTML links are defined with the ```<a>``` tag:

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
1. Absolute URL - Links to an external image that is hosted on another website. Example: src="https://www.remove.bg/sample_images.jpg".

2. Relative URL - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="bird-thumbnail.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/bird-thumbnail.jpg".
```

6. The ```<br>``` tag defines a line break, and is an empty element without a closing tag.

```html
<p> Hi <br> This <br> Is <br> The <br> Use <br> Of <br> Break <br> Tag </p>
```
```
Note: HTML is Not Case Sensitive
```

7. The ```style``` attribute is used to add styles to an element, such as color, font, size, and more.

```html
<p style="color:red;">This is a red paragraph.</p>
```

8. The lang attribute inside the <html> tag declares the language of the Web page. This is meant to assist search engines and browsers.

```html
<html lang="en">
```