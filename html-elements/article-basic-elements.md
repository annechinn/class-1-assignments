# Article - Basic Elements

## Article Part 1 - Basic HTML Elements

You task for this assignment is to use your knowledge of basic HTML elements to build a web page for an article.  Feel free to use whatever topic you want for your article.

In general, you want to start off with an rough design/schematic for your page before you start. A **wireframe** is the term used for the mockup created to visualize the initial rendering of the page. A wireframe is a rough visual representation of the page.  Here is the wireframe for the page you are going to create for this assignment.

![](../.gitbook/assets/image%20%2835%29%20%281%29.png)

## Create index.html

Create your new HTML page in your project folder. Name it index.html.  Once you have generated your boiler-plate HTML, don't forget to change the &lt;title&gt; element to something more meaningful for your page.

## Lorem Ipsum Text

A technique front-end developers use when they need some text to display in prototypes \(non-production code\), is to use sample text supplied by sites like [https://loremipsum.io/](https://loremipsum.io/).

![](../.gitbook/assets/image%20%2832%29.png)

You can specify whether you want paragraphs or sentences, and it will generate some sample text that you can then copy and use in your pages.

Not only does it prevent you from having to come up with your own narrative, but it also keeps the people reviewing your web page from getting distracted by the text, and instead focus on the overall design review.

In this assignment, there are several places where you will need to use some Lorem Ipsum text.

## Title Section

This is the title for your entire page. Use an `h1` element.

For the author byline, use an `<p>` element.

## Video Section

You can add a video to your page using the &lt;video&gt; element. There are several attributes necessary to include the various controls on the video. The attributes for adding controls to the the video are: autoplay, muted, and loop. They are boolean attributes. Just placing the attribute on the element \(with no associated value\) is all that is needed to activate the functionality. For example, here is now those attributes would be specified.

```markup
<video src="" controls autoplay muted loop />
```

| Attribute | Purpose |
| :--- | :--- |
| src | The value of the src attribute can be a path to a local image or an URL to a remote video. |
| controls | whether the control panel is visible.  |
| autoplay | whether it starts automatically |
| muted | whether the audio is muted by default |
| loop | whether the video plays in a loop |

Look on [pexels.com](http://www.pexels.com) for free videos on your topic.  Enter "videos \[topic\]" in the search box, then right click on a video to bring up the context menu and click the "Copy video address" option. You will use that URL for the **src** attribute of the `<video>` element.

![](../.gitbook/assets/image%20%2839%29.png)

After the article, insert some Lorem Ipsum text to describe the video.

## Article TOC \(Table of Contents\)

Before the three sections, there is a heading, followed by a list of three items. They are links to the sections further down the page. Clicking on the link will scroll down to that section of the page. Use an `h2` element for this heading. To create the list, use `ul`/`li` elements with an `a` element inside each `li` element to create the links to each of the sections.

#### Internal Page Links

Most of the time the value of the href attribute on the &lt;a&gt; element is the URL for an external page with in the website, or a page within another website \(usually launches a new tab for this type\). 

But it is also possible to set the href attribute to the id of another element in the same page. Click on this type of hyper-link will cause the target element to scroll into view. This is particularly useful for very long articles where there is an index to sections at the top and clicking on a link in the index scrolls the page down to the appropriate section.

 For our article we are going to use this technique to link the items in the TOC list to their associated sections further down in the article.

In order to do this, you will need to give each section heading \(the `h3` element\) an id attribute with a unique value. Then, in the `a` element, you will specify that **\#id** as the value for the href attribute.

For example, here is how we could create a hyper-link to the section heading further down the page.

```markup
<a href="#section1">Section 1</a>

<!-- more stuff here -->

<h3 id="section1">Section1</h3>
```

## Article Detail Sections

There are going to be three different sections in the article, each detailing something about your topic. 

For each section, there will be:

* a heading - use an `h3` element
* followed by a paragraph of text - use a `p` element
* followed by an image about the topic - use an `img` element
* and finally, a caption under the image \(byline for the image author\) - use a `p` element.

Inside the paragraph of text, embed a hyper-link to an external page about your topic.  For example, if your topic is soccer, you could link to your favorite site about soccer. Remember to use the **target** attribute on the `a` element with a value of "\_blank" to make the new page come up in a separate window.

Just like you did for your video, you can use the [pexels.com](http://www.pexels.com) or [unsplash.com](http://www.unsplash.com) websites to get access to free images to use in your web page. Again, just right click on the image, and choose the "Copy image address" option to copy the URL for the image. Use that URL as the value for the src attribute on the `img` element.

![](../.gitbook/assets/image%20%2846%29.png)

## Sample Completed Article

Here is what a sample article with the topic of jelly fish looks like. Only the first section is included in the screen capture. There would be two more sections following the Pink Jelly section: one for the Orange Jelly and one for the Yellow Jelly. Clicking on the links in the Meet the Jellies TOC would cause the page to scroll down and bring the corresponding into view.

![](../.gitbook/assets/image%20%2841%29.png)

Remember to get in the habit of using git ACP \(add, commit, push\) to save snapshots of your work whenever you feel you have reached a new milestone and would like to preserve your progress. 

When you are done, do it one last time to make sure your final work is on GitHub for your instructor to review.

