# HTML(IMAGE.COLOR.TEXT)

## Image

> On the Internet, images are used for all kinds of reasons: to enhance websites, to illustrate stories, in ad displays, to present products or services, as stand-alone “a picture is worth a thousand words” meaning-rich tools, and sure, on social media.

#### Add image in html page

In order to put a simple image on a webpage, we use the *img* element. This is an empty element > meaning that it has no text content or closing tag that requires a minimum of one attribute to be useful — src (sometimes spoken as its full title, source. The src attribute contains a path pointing to the image you want to embed in the page, which can be a relative or absolute URL, in the same way as href attribute values in *a* element.

#### Format my image

Most normal image formats (JPEG, GIF, PNG, BMP, TIFF, SVG) will work in most situations most of the time.

#### Edit my image

The traditional way to avoid this was to provide width and height attributes in the *img* markup so even when the browser has just the HTML, it is still able to allocate the appropriate amount of space.
> Controlling Image Width: Before the advent of CSS, the display width of an image was controlled by the width attribute. This usage has been deprecated. In the absence of any CSS rules defining the display width of the image, it will still work in most browsers. However, this is specifically contrary to the HTML5 specification.
> Responsive Image Widths:Generally speaking, you usually don’t want to control the exact width of an image. Every visitor who comes to your website has a potentially different size screen. If you specify the width, it may be much too small for some users and much too big for others. Most of the time, the best option is to make sure that your image is inside of a responsive (percent-based) container and then let it fill the container.
**eXAMPLE OF HTML img**

(![LAB02](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2020/07/html-images-df.jpg)

-------

### HTML5: Figure and Figure Caption

The HTML *figure* Figure With Optional Caption element represents self-contained content, potentially with an optional caption, which is specified using the *figcaption* element. The figure, its caption, and its contents are referenced as a single unit.

## color

Just starting your website or need a refresher? Our tutorials section has something for everyone, from basic HTML and CSS color guides to more advanced techniques in SCSS.
Color codes are ways of representing the colors we see everyday in a format that a computer can interpret and display. Commonly used in websites and other software applications, there are a variety of formats, including Hex color codes, RGB and HSL values, and HTML color names, amongst others.

HEX COLOR CODES
The most popular are Hex color codes; three byte hexadecimal numbers (meaning they consist of six digits), with each byte, or pair of characters in the Hex code, representing the intensity of red, green and blue in the color respectively.
Hex code byte values range from 00, which is the lowest intensity of a color, to FF which represents the highest intensity. The color white, for example, is made by mixing each of the three primary colors at their full intensity, resulting in the Hex color code of #FFFFFF.

**eXAMPLE OF HTML color**

(![LAB02](https://www.computerhope.com/cdn/color-code.png)

-------

## text

One of HTML's main jobs is to give text structure and meaning (also known as semantics) so that a browser can display it correctly. This article explains the way HTML can be used to structure a page of text by adding headings and paragraphs, emphasizing words, creating lists, and more.
> headings and paragraphs:
Most structured text consists of headings and sparagraphs, whether you are reading a story, a newspaper, a college textbook, a magazine, etc.
Structured content makes the reading experience easier and more enjoyable.
In HTML, each paragraph has to be wrapped in a *p* elemnt and There are six heading elements: *h1*, *h2*, *h3*, *h4*, *h5*, and *h6*. Each element represents a different level of content in the document; *h1* represents the main heading, *h2* represents subheadings, *h3* represents sub-subheadings, and so on.

**EXAMPLE OF HTML TEXT**

![LAB02](https://static.javatpoint.com/htmlpages/images/html-heading.png)

-------

# JPEG vs PNG vs GIF — which image format to use and when?

Theres alot of image formats avaiable each one has a specific use case.we would only be looking and see three most common type used in website and mobile app,jpeg,png and gif.

> jpeg : stands for “Joint Photographic Experts Group”. It's a standard image format for containing lossy and compressed image data. Despite the huge reduction in file size JPEG images maintain reasonable image quality.
> png : stands for Portable Network Graphics and is another raster image type. The main difference between a PNG and a JPG is that a PNG file can have a transparent background and is generally larger and of higher quality. PNGs are great for interactive documents such as web pages but are not suitable for print.
> gif: The Graphics Interchange Format s a bitmap image format that was developed by a team at the online services provider CompuServe led by American computer .
(![LAB5](https://pctechmag.com/wp-content/uploads/2015/09/jpeg-png-gif1-960x420.jpg)

- Transparency:transparency indicates something that is completely invisible.we can use it to make logo and icons transparency to placed on background.

> jpeg: images don’t support transparency .
> png : it support transparency in two way,1- nserting an alpha channel that allows partial transparency or by declaring a single colour as transparen. 2 -Partial transparency makes the edges blend smoothly into the background.
> gif: support transparency by declaring a single colour in the colour palette as transparent.

- color:

 > jpeg :support around 16 million colours. This is what makes them suitable for storing images of natural scenes.
 > png : NG8 and PNG24. PNG8 can support upto 256 colours whereas PNG24 can handle upto 16 million colours like a JPEG image. Use PNG8 for simple shapes with fewer colours and PNG24 for high quality, complex logos and shapes with rounded corners on a transparent background.
 > gif : are limited to 256 colours.

- Animation :You can upload multiple PNG or JPG images to our animated PNG maker, choose the order, frame duration and transition effect (if you want to), and it will assemble animated PNG from these images. With this method you can use the full potential of animated PNG and create images with much broader color palette than GIFs
