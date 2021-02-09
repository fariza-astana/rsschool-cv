<!DOCTYPE html>
<html>
<head>
<title>cv</title>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<style type="text/css">
/* GitHub stylesheet for MarkdownPad (http://markdownpad.com) */
/* Author: Nicolas Hery - http://nicolashery.com */
/* Version: b13fe65ca28d2e568c6ed5d7f06581183df8f2ff */
/* Source: https://github.com/nicolahery/markdownpad-github */

/* RESET
=============================================================================*/

html, body, div, span, applet, object, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, pre, a, abbr, acronym, address, big, cite, code, del, dfn, em, img, ins, kbd, q, s, samp, small, strike, strong, sub, sup, tt, var, b, u, i, center, dl, dt, dd, ol, ul, li, fieldset, form, label, legend, table, caption, tbody, tfoot, thead, tr, th, td, article, aside, canvas, details, embed, figure, figcaption, footer, header, hgroup, menu, nav, output, ruby, section, summary, time, mark, audio, video {
  margin: 0;
  padding: 0;
  border: 0;
}

/* BODY
=============================================================================*/

body {
  font-family: Helvetica, arial, freesans, clean, sans-serif;
  font-size: 14px;
  line-height: 1.6;
  color: #333;
  background-color: #fff;
  padding: 20px;
  max-width: 960px;
  margin: 0 auto;
}

body>*:first-child {
  margin-top: 0 !important;
}

body>*:last-child {
  margin-bottom: 0 !important;
}

/* BLOCKS
=============================================================================*/

p, blockquote, ul, ol, dl, table, pre {
  margin: 15px 0;
}

/* HEADERS
=============================================================================*/

h1, h2, h3, h4, h5, h6 {
  margin: 20px 0 10px;
  padding: 0;
  font-weight: bold;
  -webkit-font-smoothing: antialiased;
}

h1 tt, h1 code, h2 tt, h2 code, h3 tt, h3 code, h4 tt, h4 code, h5 tt, h5 code, h6 tt, h6 code {
  font-size: inherit;
}

h1 {
  font-size: 28px;
  color: #000;
}

h2 {
  font-size: 24px;
  border-bottom: 1px solid #ccc;
  color: #000;
}

h3 {
  font-size: 18px;
}

h4 {
  font-size: 16px;
}

h5 {
  font-size: 14px;
}

h6 {
  color: #777;
  font-size: 14px;
}

body>h2:first-child, body>h1:first-child, body>h1:first-child+h2, body>h3:first-child, body>h4:first-child, body>h5:first-child, body>h6:first-child {
  margin-top: 0;
  padding-top: 0;
}

a:first-child h1, a:first-child h2, a:first-child h3, a:first-child h4, a:first-child h5, a:first-child h6 {
  margin-top: 0;
  padding-top: 0;
}

h1+p, h2+p, h3+p, h4+p, h5+p, h6+p {
  margin-top: 10px;
}

/* LINKS
=============================================================================*/

a {
  color: #4183C4;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

/* LISTS
=============================================================================*/

ul, ol {
  padding-left: 30px;
}

ul li > :first-child, 
ol li > :first-child, 
ul li ul:first-of-type, 
ol li ol:first-of-type, 
ul li ol:first-of-type, 
ol li ul:first-of-type {
  margin-top: 0px;
}

ul ul, ul ol, ol ol, ol ul {
  margin-bottom: 0;
}

dl {
  padding: 0;
}

dl dt {
  font-size: 14px;
  font-weight: bold;
  font-style: italic;
  padding: 0;
  margin: 15px 0 5px;
}

dl dt:first-child {
  padding: 0;
}

dl dt>:first-child {
  margin-top: 0px;
}

dl dt>:last-child {
  margin-bottom: 0px;
}

dl dd {
  margin: 0 0 15px;
  padding: 0 15px;
}

dl dd>:first-child {
  margin-top: 0px;
}

dl dd>:last-child {
  margin-bottom: 0px;
}

/* CODE
=============================================================================*/

pre, code, tt {
  font-size: 12px;
  font-family: Consolas, "Liberation Mono", Courier, monospace;
}

code, tt {
  margin: 0 0px;
  padding: 0px 0px;
  white-space: nowrap;
  border: 1px solid #eaeaea;
  background-color: #f8f8f8;
  border-radius: 3px;
}

pre>code {
  margin: 0;
  padding: 0;
  white-space: pre;
  border: none;
  background: transparent;
}

pre {
  background-color: #f8f8f8;
  border: 1px solid #ccc;
  font-size: 13px;
  line-height: 19px;
  overflow: auto;
  padding: 6px 10px;
  border-radius: 3px;
}

pre code, pre tt {
  background-color: transparent;
  border: none;
}

kbd {
    -moz-border-bottom-colors: none;
    -moz-border-left-colors: none;
    -moz-border-right-colors: none;
    -moz-border-top-colors: none;
    background-color: #DDDDDD;
    background-image: linear-gradient(#F1F1F1, #DDDDDD);
    background-repeat: repeat-x;
    border-color: #DDDDDD #CCCCCC #CCCCCC #DDDDDD;
    border-image: none;
    border-radius: 2px 2px 2px 2px;
    border-style: solid;
    border-width: 1px;
    font-family: "Helvetica Neue",Helvetica,Arial,sans-serif;
    line-height: 10px;
    padding: 1px 4px;
}

/* QUOTES
=============================================================================*/

blockquote {
  border-left: 4px solid #DDD;
  padding: 0 15px;
  color: #777;
}

blockquote>:first-child {
  margin-top: 0px;
}

blockquote>:last-child {
  margin-bottom: 0px;
}

/* HORIZONTAL RULES
=============================================================================*/

hr {
  clear: both;
  margin: 15px 0;
  height: 0px;
  overflow: hidden;
  border: none;
  background: transparent;
  border-bottom: 4px solid #ddd;
  padding: 0;
}

/* TABLES
=============================================================================*/

table th {
  font-weight: bold;
}

table th, table td {
  border: 1px solid #ccc;
  padding: 6px 13px;
}

table tr {
  border-top: 1px solid #ccc;
  background-color: #fff;
}

table tr:nth-child(2n) {
  background-color: #f8f8f8;
}

/* IMAGES
=============================================================================*/

img {
  max-width: 100%
}
</style>
</head>
<body>
<img src="https://avatars.githubusercontent.com/u/71820246?s=460&u=1ed278d910724a729c6a2f5d4949be81aac7a242&v=4" width="200" height="200" />
<h2>Fariza Amanzholova</h2>
<h3><strong>Junior Frontend Developer</strong></h3>
<h5>MY BACKGROUND</h5>
<blockquote>
<p>Programming gets me excited. I am a woman of character and determination. I am a Bachelor in translation studies but  I  study programming by myself - I know what I need and it is my goal. My slogan: &quot;Learn. See more.Do more&quot;.</p>
</blockquote>
<h5>SKILLS</h5>
<ul>
<li>HTML5</li>
<li>CSS3</li>
<li>JS</li>
<li>Figma</li>
<li>Git</li>
<li>SQL</li>
<li>Power BI </li>
</ul>
<h5>EXAMPLE OF HTML CODE</h5>
<pre><code>     &lt;h1 class=&quot;title&quot;&gt;Fariza Amanzholova&lt;/h1&gt;
     &lt;h2 class=&quot;title&quot; id=&quot;jun&quot;&gt;Junior Frontend Developer&lt;/h2&gt;
     &lt;span class=&quot;hom&quot;&gt;
     &lt;h3 class=&quot;subtitle&quot; id=&quot;home&quot;&gt;ABOUT ME&lt;/h3&gt;&lt;/span&gt;
     &lt;p&gt;My name is Fariza. I live in Nur-Sultan city, Kazakhstan. 
        I am a Bachelor in translation studies but I like &lt;strong&gt;programming&lt;/strong&gt;, it &lt;strong&gt;gets me excited&lt;/strong&gt;.
        I am a woman of character and determination, my slogan is &quot;Learn. See more. Do more.&quot;. By the way, my hobbies are photography and climbing! &lt;/p&gt;
</code></pre>

<h5>EDUCATION BACKGROUND</h5>
<p><em>Courses and Certificates:</em></p>
<ul>
<li>Java Script Course (Rolling Scopes School + Projects)</li>
<li>Frontend Developer Course (SkillFactory Academy + Projects)</li>
<li>The Data Scientist's Toolbox (Johns Hopkins University)</li>
<li>SQL </li>
<li>Data Analysis and Visualization with Microsoft Power BI (Nazarbayev University and Yekaterina Rekhert)</li>
<li>Programming for Everybody with Python (University of Michigan)</li>
<li>Python for Everyone (American Space Almaty + Project)</li>
<li>R Programming (Johns Hopkins University)</li>
<li>Основы фотографии (Novosibirsk State University)</li>
</ul>
<p><em>Universities:</em></p>
<ul>
<li>Kazakh University of International Relations and World Languages <em>(Bachelor in Translation Studies, 2009-2013)</em></li>
<li>East China University of Science and Technology, Shanghai <em>(Chinese Language and Culture Program, 2013-2014)</em></li>
</ul>
<h5>LANGUAGES</h5>
<ul>
<li>English - Upper Intermediate</li>
<li>Russian - Fluently</li>
<li>Chinese - Elementary</li>
<li>Kazakh - Native</li>
</ul>
<hr />
<h5>REACH ME AT:</h5>
<ul>
<li>
<p><em>Mobile:</em>
<strong>+8 708 350 0297</strong></p>
</li>
<li>
<p><em>Email:</em> 
<strong><a href="famanzholova@gmail.com">famanzholova@gmail.com</a></strong></p>
</li>
<li>
<p><em>My Web Portal:</em> 
<strong><a href="https://fariza-astana.github.io">fariza-astana.github.io</a></strong></p>
</li>
<li>
<p><em>I am in LinkedIn:</em>   <strong><a href="www.linkedin.com/in/fariza-amanzholova">Fariza Amanzholova</a></strong></p>
</li>
</ul>

</body>
</html>
<!-- This document was created with MarkdownPad, the Markdown editor for Windows (http://markdownpad.com) -->
