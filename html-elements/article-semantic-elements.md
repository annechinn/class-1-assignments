# Article - Semantic Elements

## Article Part 2 - Semantic HTML Elements

You task for this assignment is to improve your topic article to use semantic elements. This is the basic layout from the last assignment.

![](../.gitbook/assets/image%20%2835%29.png)

## Create index.html

Create your new HTML page in your project folder. Name it index.html.  Copy the contents of the index.html from your previous article assignment into this project as a starting point.

## Section Element

The first step is to use the `<section>` element to wrap sections of the HTML element tree that are logically grouped together so that you can use that to later style each section. In the screen capture below, each of these elements should be wrapped in a `<section>` element. I have left out the last two topic sections. They would follow the same pattern as Section 1.

![](../.gitbook/assets/image%20%2833%29.png)

Here is an example, of wrapping the elements for Section 1, which is for the Pink Jelly section in my example.

```markup
<!--------------------- Pink Jelly ---------------------->
<section>
  <h3 id="pink-jelly">Pink Jelly</h3>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing
  elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Egestas tellus rutrum tellus
  Tellus rutrum tellus pellentesque eu tincidunt tortor aliquam nulla facilisi. Libero justo laoreet sit amet cursus sit.
  </p>
  <p>Vel quam elementum pulvinar etiam non quam lacus suspendisse. Tincidunt dui ut ornare lectus sit amet
      est placerat in. Lectus nulla at volutpat diam ut  venenatis tellus.
  </p>
  <p> Sally Smith</p>
</section>
```

You should have the following sections:

* Article Title Section
* Video Section
* Article TOC Section
* Each Article Topic Section

## Title Section

Use the `<address>` element to display the author's name instead of the `<p>` element.

[MDN Docs Link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/address)

## Article Detail Sections

Use the &lt;figure&gt; element to wrap both the image and the caption below the image.

[MDN Docs Link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/figure)

## Top-level Layout Elements

Inside the `<body>` element, wrap all of the content with an `<article>` element, to indicate that the content is an article.

Then, wrap the portion labelled header below with a `<header>` element and the portion labelled main with a `<main>` element.

![](../.gitbook/assets/image%20%2836%29.png)

[MDN Docs Link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/main)

That's it. You now have a document ready for for the next step: applying some CSS. 

Use the ACP git commands to update GitHub with your work.

