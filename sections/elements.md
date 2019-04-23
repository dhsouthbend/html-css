[<<<Back](basic.md) | [Next>>>](p_and_h.md)

# Tags and Elements

Tags and elements are the structuring components of html webpages.

**Elements** identify the different parts of a page, such as paragraphs, headings, titles, body text, images and more. Elements are demarcated by tags which enclose the content of an element (ex. `<head>` and `</head>` are tags that denote the head element of your page).

**Tags** demarcate elements in one of two ways. As with the paragraph element below, an element can have an opening and a closing tag, with the content in between. 

```html
<p>This is a paragraph.</p>
	
<p>
	This is also a paragraph.
</p>
```
	
Elements which have an opening and closing tag can have other elements inside them. Inside the paragraph element below is a strong element, which emphasizes the included text, usually by making it bold.

```html
<p>
	When I came home from school, I saw he had <strong>stolen</strong> my chocolate pudding.
</p>
```

Other elements have self-closing tags as with the image element below. These tags are also called **void tags**. 

```html
<img src="image.jpeg">
```
These elements don't require a separate closing tag. Closing tags aren't needed because you wouldn't add content inside these elements. For example, it doesn't make sense to add any additional content inside an image. 

Below is HTML that adds alternative text to an image—or text that describes the image. This information added is an attribute—or something that modifies the default functionality of an element.

```html
<img alt="This is an image" src="image.jpeg">
```
Adding alternative text to an image, as was done in this example, is vitally important. That information makes the image more accessible to those viewing your site. For instance, users with poor vision who may not be able to see your image will still understand what it is and why it's there if you provide alternative text describing it.

If you look back at the basic template in your `index.html` file, you'll see that the main sections of your file have opening and closing tags. Each of these main elements will eventually hold many other elements, many of which will be the content of our website.

[<<<Back](basic.md) | [Next>>>](p_and_h.md)
