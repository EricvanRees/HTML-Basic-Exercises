# Basic HTML exercises

**1. How to comment HTML tags?**

<!-- This is an HTML comment -->

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
