# image in html

The <img> tag is used to embed an image in an HTML page. Images are not technically inserted into a web page; images are linked to web pages. ... src - Specifies the path to the image. alt - Specifies an alternate text for the image, if the image for some reason cannot be displayed.
In HTML, you can add images in a webpage using the <img> tag. The <img> is an empty tag which means it does not have a closing tag. This tag requires some set of attributes to specify the size, alignment, and other properties of an image.

## Making CSS Set Background Image

The CSS background-image adds images as backgrounds of HTML elements. Such backgrounds can either be images. The background image url() lets you set any image as the background.

### Adding Multiple Pictures

One element can have multiple background images in CSS. You need to separate them by commas and remember that the images stack on one another. The first image is the main layer, meaning that other pictures are behind it.Another option is to apply the background shorthand and include all styling properties for the background in one declaration

### Setting background-size

The background-size styling property has three possible values:

- auto: the default value which tells the browser to decide the best size for the background image.
- cover: this value guarantees that the background image always covers the whole container (even if the image needs to be stretched or cut).
- contain: this value indicates that the actual image size needs to be shown even if it does not fill the container.

### Sizes of Multiple Pictures

The background-size property accepts multiple values to set the sizes for several background images. The sizes apply according to the position of background images in the declaration list.

### Full-Size Website Background

Sometimes it is necessary to make the background image in CSS to always cover the whole browser window.

The following example aims to do the following things:

- Images fill the whole page and leave no whitespace.
- Images are scaled if necessary.
- The image is centered on the page.
- Images do not trigger a scroll bar.
- Images keep their proportions.

> This example follows these steps:
1- Use the <html>.
2 -Center the background image and set a fixed position for it.
3 -Set the background-size to cover.
4- However, this technique has issues in Internet Explorer. Therefore, we offer you an alternative of making CSS set a centered background image and keeping its aspect ratio even though the image covers the whole page.
  
### Positioning Background Images

The background-origin property allows us to position the CSS background image according to the content, borders, or padding.
This property accepts three values:
. border-box: positions the image to be relative to the border box.
. padding-box: (the default value) positions the image to be relative to the padding box.
. content-box: positions the image to be relative to the content box.

![ Image ](https://i.pinimg.com/originals/03/9f/02/039f0200ea6f073df03027a955184dc8.jpg)

## Practical Information

- Search engine optimization
- Using analytics to understand visitors
- Putting your site on the web
- To wrap up the book we are going to look at some practical information that will help you launch a successful site.

> There are entire books written about each of the topics covered in this chapter but I will introduce you to the key themes that each subject deals with and give you pointers for what you need to be considering. You will see:

- The basics of search engine optimization
- Using analytics to understand how people are using your site after it has launched
- Putting your site on the web

### Steps to a Google-friendly site

#### Give visitors the information they're looking for

Provide high-quality content on your pages, especially your homepage. This is the single most important thing to do. If your pages contain useful information, their content will attract many visitors and entice webmasters to link to your site. In creating a helpful, information-rich site, write pages that clearly and accurately describe your topic. Think about the words users would type to find your pages and include those words on your site.

#### Make sure that other sites link to yours

Links help our crawlers find your site and can give your site greater visibility in our search results. When returning results for a search, Google uses sophisticated text-matching techniques to display pages that are both important and relevant to each search. Google interprets a link from page A to page B as a vote by page A for page B. Votes cast by pages that are themselves "important" weigh more heavily and help to make other pages "important."

Keep in mind that our algorithms can distinguish natural links from unnatural links. Natural links to your site develop as part of the dynamic nature of the web when other sites find your content valuable and think it would be helpful for their visitors. Unnatural links to your site are placed there specifically to make your site look more popular to search engines. Some of these types of links (such as link schemes and doorway pages) are covered in our Webmaster Guidelines.

Only natural links are useful for the indexing and ranking of your site.

#### Make your site easily accessible

Build your site with a logical link structure. Every page should be reachable from at least one static text link.

Use a text browser, such as Lynx, to examine your site. Most spiders see your site much as Lynx would. If features such as JavaScript, cookies, session IDs, DHTML, or Macromedia Flash keep you from seeing your entire site in a text browser, then spiders may have trouble crawling it.

#### Things to avoid

Don't fill your page with lists of keywords, attempt to "cloak" pages, or put up "crawler only" pages. If your site contains pages, links, or text that you don't intend visitors to see, Google considers those links and pages deceptive and may ignore your site.

Don't feel obligated to purchase a search engine optimization service. Some companies claim to "guarantee" high ranking for your site in Google's search results. While legitimate consulting firms can improve your site's flow and content, others employ deceptive tactics in an attempt to fool search engines. Be careful; if your domain is affiliated with one of these deceptive services, it could be banned from our index.

Don't use images to display important names, content, or links. Our crawler doesn't recognize text contained in graphics. Use ALT attributes if the main content and keywords on your page can't be formatted in regular HTML.

Don't create multiple copies of a page under different URLs. Many sites offer text-only or printer-friendly versions of pages that contain the same content as the corresponding graphic-rich pages. If your site has identical content that can be reached via different URLs, there are several ways of indicating the canonical (preferred) version of a page. More information about canonicalization.

![ Image ](https://www.nhancedigital.com/wp-content/uploads/2018/01/linkbuilding.jpg)
