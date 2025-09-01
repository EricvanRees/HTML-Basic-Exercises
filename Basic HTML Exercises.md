# Basic HTML exercises

**1. How to comment HTML tags?**

\<!-- This is an HTML comment -->

**2. How to create a hyperlink?**

\<a href="url">link text\</a>

**3. How to author an abbreviation or an acronym?**

Using the <abbr> tag.
For example: The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.

**4. What is the correct way to write address in an HTML document?**

'www.google.com'

**5. How to create an area inside an image-map?**

\<img src="workplace.jpg" alt="Workplace" usemap="#workmap" width="400" height="379">

\<map name="workmap">
  \<area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
  \<area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">
  \<area shape="circle" coords="337,300,44" alt="Cup of coffee" href="coffee.htm">
\</map>

**6. Create an HTML document which uses article element?**

\<article>
\<h2>Google Chrome</h2>
\<p>Google Chrome is a web browser developed by Google, released in 2008. Chrome is the world's most popular web browser today!</p>
\</article>

**7. Create an HTML document which uses aside element?**

\<p>My family and I visited The Epcot center this summer. The weather was nice, and Epcot was amazing! I had a great summer together with my family!\</p>

\<aside>
\<h4>Epcot Center</h4>
\<p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.\</p>
\</aside>

**8. How to embed audio in a HTML document?**

\<audio controls>
  \<source src="horse.ogg" type="audio/ogg">
  \<source src="horse.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
\</audio>

**9. How to write bold text using HTML tags?**

\<b>and this is bold text\</b>

**10. How to specify the base URL/target for all relative URLs in a document?**

\<head>
  \<base href="https://www.w3schools.com/" target="_blank">
\</head>

**11. How to isolate a part of the text that might be formatted in a different direction from other text outside it?**

BDI stands for Bi-Directional Isolation.

The \<bdi> tag isolates a part of text that might be formatted in a different direction from other text outside it.

This element is useful when embedding user-generated content with an unknown text direction.

Example:

<ul>
  <li>User <bdi>hrefs</bdi>: 60 points</li>
  <li>User <bdi>jdoe</bdi>: 80 points</li>
  <li>User <bdi>إيان</bdi>: 90 points</li>
</ul>

**12. How to override the current text direction?**

BDO stands for Bi-Directional Override.

The \<bdo> tag is used to override the current text direction.

Example:

\<bdo dir="rtl">
This text will go right-to-left.
\</bdo>

**13. How to define a section that is quoted from another source?**

The \<blockquote> tag specifies a section that is quoted from another source.

Example:

<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 50 years, WWF has been protecting the future of nature. The world's leading conservation organization, WWF works in 100 countries and is supported by 1.2 million members in the United States and close to 5 million globally.
</blockquote>


**14. How to define the document's body?**

The \<body> tag defines the document's body.

\<body>
  \<h1>This is a heading\</h1>
  \<p>This is a paragraph.\</p>
\</body>

**15. How to define a single line break?**

The \<br> tag inserts a single line break.

Example:

\<p>To force\<br> line breaks\<br> in a text,\<br> use the br\<br> element.</p>

**16. How to define a clickable button?**

\<button type="button">Click Me!</button>

**17. How to draw graphics, on the fly, via scripting?**

The \<canvas> tag is used to draw graphics, on the fly, via scripting (usually JavaScript).

\<canvas id="myCanvas">
Your browser does not support the canvas tag.
\</canvas>

\<script>
let canvas = document.getElementById("myCanvas");
let ctx = canvas.getContext("2d");
ctx.fillStyle = "#FF0000";
ctx.fillRect(0, 0, 80, 80);
\</script>

**18. How to define a table caption?**

The \<caption> tag defines a table caption.

The \<caption> tag must be inserted immediately after the <table> tag.

\<table>
  \<caption>Monthly savings\</caption>
  \<tr>
    \<th>Month\</th>
    \<th>Savings\</th>
  \</tr>
  \<tr>
    \<td>January\</td>
    \<td>$100\</td>
  \</tr>
\</table>

**19. How to define the title of an HTML document?**

\<title>Document\</title>

**20. How to specify the column properties of each column within a colgroup element?**

The \<colgroup> tag specifies a group of one or more columns in a table for formatting.

The \<colgroup> tag is useful for applying styles to entire columns, instead of repeating the styles for each cell, for each row.

Example:

\<colgroup>
    \<col span="2" style="background-color:red">
    \<col style="background-color:yellow">
  \</colgroup>
  
  **21. How to define a piece of code?**
  **a. How to render as emphasized text?**
  
  The \<em> tag is used to define emphasized text. The content inside is typically displayed in italic.

  **b. How to define important text?**

  The \<strong> tag is used to define text with strong importance. The content inside is typically displayed in bold.


