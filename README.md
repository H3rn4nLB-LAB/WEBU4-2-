# WEBU4-2-
Práctica del Trimestre
# Auto detect text files and perform LF normalization
* text=auto
web4u/
│
├── index.html
├── html.html
├── css.html
├── svg.html
│
├── /css/
│    ├── style.css
│    └── print.css
│
├── /img/
│    ├── html-logo.png
│    ├── css-logo.png
│    ├── svg-logo.png
│    ├── example1.png
│    ├── example2.png
│    ├── example3.png
│    └── (…more generated demo images)
│
└── /pdf/
     ├── html.pdf   
     ├── css.pdf
     ├── svg.pdf


/* index.html*/

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Web4U – Learn HTML, CSS & SVG</title>
    <link rel="stylesheet" href="css/style.css">
</head>

<body>

<header>
    <h1>Web4U</h1>
    <h2>Bilingual Web Development Tutorials (English / Español)</h2>
</header>

<nav>
    <a href="index.html" class="active" title="Home page">Home</a>
    <a href="html.html" title="HTML tags tutorial">HTML</a>
    <a href="css.html" title="CSS properties tutorial">CSS</a>
    <a href="svg.html" title="SVG tags tutorial">SVG</a>
</nav>

<main>

<h2>Welcome / Bienvenido</h2>
<p>
    Learn HTML, CSS and SVG with bilingual explanations, examples, images, 
    and PDF download options.  
    Aprende HTML, CSS y SVG con explicaciones bilingües, ejemplos, imágenes 
    y versiones en PDF.
</p>

<h3>Select a Technology / Selecciona una tecnología</h3>

<div style="display:flex; gap:30px; flex-wrap:wrap;">
    <div>
        <a href="html.html" title="Go to HTML tutorials">
            <img src="img/html-logo.png" alt="HTML logo" width="170">
        </a>
    </div>
    <div>
        <a href="css.html" title="Go to CSS tutorials">
            <img src="img/css-logo.png" alt="CSS logo" width="170">
        </a>
    </div>
    <div>
        <a href="svg.html" title="Go to SVG tutorials">
            <img src="img/svg-logo.png" alt="SVG logo" width="170">
        </a>
    </div>
</div>

</main>

<footer>
    <p>Web4U © 2025 – Educational Project</p>
</footer>

</body>
</html>

/*html.html*/

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Web4U – HTML Tags</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="css/print.css" media="print">
</head>

<body>

<header>
    <h1>HTML Tag Tutorials</h1>
</header>

<nav>
    <a href="index.html" title="Home page">Home</a>
    <a href="html.html" class="active" title="You are here: HTML tutorials">HTML</a>
    <a href="css.html" title="CSS tutorials">CSS</a>
    <a href="svg.html" title="SVG tutorials">SVG</a>
</nav>

<main>

<h2 id="top">HTML Tags – English / Español</h2>
<p>
    <a href="pdf/html.pdf" title="Download PDF (non-HTML resource)">Download PDF</a>
</p>

<div class="toc">
    <strong>Table of Contents</strong>
    <ul>
        <li><a href="#p-tag">&lt;p&gt; – Paragraph</a></li>
        <li><a href="#img-tag">&lt;img&gt; – Image</a></li>
        <li><a href="#a-tag">&lt;a&gt; – Link</a></li>
        <li><a href="#ul-tag">&lt;ul&gt; – Unordered list</a></li>
        <li><a href="#table-tag">&lt;table&gt; – Table</a></li>
    </ul>
</div>


<!-- ███████████████████████████ -->
<!-- 1. PARAGRAPH -->
<!-- ███████████████████████████ -->

<h3 id="p-tag">&lt;p&gt; – Paragraph</h3>

<p><b>English:</b> Defines a paragraph of text.</p>
<p><b>Español:</b> Define un párrafo de texto.</p>

<pre><code>&lt;p&gt;This is a paragraph.&lt;/p&gt;
</code></pre>

<img class="example" src="img/example1.png" alt="Paragraph example output">

<p>
More info:  
<a href="https://html.spec.whatwg.org/multipage/grouping-content.html#the-p-element" 
   title="Paragraph element specification">W3C Spec</a>
</p>


<!-- ███████████████████████████ -->
<!-- 2. IMAGE -->
<!-- ███████████████████████████ -->

<h3 id="img-tag">&lt;img&gt; – Image</h3>

<p><b>English:</b> Embeds an image into a page.</p>
<p><b>Español:</b> Inserta una imagen en la página.</p>

<pre><code>&lt;img src="cat.jpg" alt="A cat"&gt;
</code></pre>

<img class="example" src="img/example2.png" alt="Image tag example">

<p>
More info:
<a href="https://html.spec.whatwg.org/multipage/embedded-content.html#the-img-element"
   title="Image element specification">W3C Spec</a>
</p>


<!-- ███████████████████████████ -->
<!-- 3. ANCHOR -->
<!-- ███████████████████████████ -->

<h3 id="a-tag">&lt;a&gt; – Link</h3>

<p><b>English:</b> Creates a hyperlink.</p>
<p><b>Español:</b> Crea un hipervínculo.</p>

<pre><code>&lt;a href="page.html"&gt;Click here&lt;/a&gt;
</code></pre>

<img class="example" src="img/example3.png" alt="Link tag example">

<p>
More info:
<a href="https://html.spec.whatwg.org/multipage/text-level-semantics.html#the-a-element"
 title="Anchor element specification">W3C Spec</a>
</p>



<!-- ███████████████████████████ -->
<!-- 4. UL -->
<!-- ███████████████████████████ -->

<h3 id="ul-tag">&lt;ul&gt; – Unordered List</h3>

<p><b>English:</b> Creates a bullet list.</p>
<p><b>Español:</b> Crea una lista con viñetas.</p>

<pre><code>&lt;ul&gt;
  &lt;li&gt;Item 1&lt;/li&gt;
  &lt;li&gt;Item 2&lt;/li&gt;
&lt;/ul&gt;
</code></pre>

<img class="example" src="img/example4.png" alt="Unordered list example">

<p>
More info:
<a href="https://html.spec.whatwg.org/multipage/grouping-content.html#the-ul-element"
 title="UL specification">W3C Spec</a>
</p>


<!-- ███████████████████████████ -->
<!-- 5. TABLE -->
<!-- ███████████████████████████ -->

<h3 id="table-tag">&lt;table&gt; – Table</h3>

<p><b>English:</b> Defines a table structure.</p>
<p><b>Español:</b> Define una tabla.</p>

<pre><code>&lt;table&gt;
  &lt;tr&gt;
    &lt;th&gt;Name&lt;/th&gt;
    &lt;th&gt;Age&lt;/th&gt;
  &lt;/tr&gt;
  &lt;tr&gt;
    &lt;td&gt;Ana&lt;/td&gt;
    &lt;td&gt;25&lt;/td&gt;
  &lt;/tr&gt;
&lt;/table&gt;
</code></pre>

<img class="example" src="img/example5.png" alt="Table example">

<p><a href="#top">Back to top / Volver arriba</a></p>

</main>

<footer>
    <p>Web4U © 2025</p>
</footer>

</body>
</html>


/*css.html*/
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Web4U – CSS Properties</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="css/print.css" media="print">
</head>

<body>

<header>
    <h1>CSS Property Tutorials</h1>
</header>

<nav>
    <a href="index.html" title="Home page">Home</a>
    <a href="html.html" title="HTML tutorials">HTML</a>
    <a href="css.html" class="active" title="You are here: CSS tutorials">CSS</a>
    <a href="svg.html" title="SVG tutorials">SVG</a>
</nav>

<main>

<h2 id="top">CSS Properties – English / Español</h2>
<p><a href="pdf/css.pdf" title="Download PDF">Download PDF</a></p>

<div class="toc">
    <ul>
        <li><a href="#color">color</a></li>
        <li><a href="#background">background-color</a></li>
        <li><a href="#margin">margin</a></li>
        <li><a href="#padding">padding</a></li>
        <li><a href="#border">border</a></li>
    </ul>
</div>


<!-- 1. COLOR -->
<h3 id="color">color</h3>

<p><b>English:</b> Sets text color.</p>
<p><b>Español:</b> Establece el color del texto.</p>

<pre><code>p {
  color: red;
}
</code></pre>

<img src="img/example6.png" class="example" alt="CSS color example">


<!-- 2. BACKGROUND -->
<h3 id="background">background-color</h3>

<p><b>English:</b> Sets background color of an element.</p>
<p><b>Español:</b> Establece el color de fondo de un elemento.</p>

<pre><code>div {
  background-color: lightblue;
}
</code></pre>

<img src="img/example7.png" class="example" alt="CSS background-color example">


<!-- 3. MARGIN -->
<h3 id="margin">margin</h3>

<p><b>English:</b> Space outside an element.</p>
<p><b>Español:</b> Espacio exterior alrededor del elemento.</p>

<pre><code>div {
  margin: 20px;
}
</code></pre>

<img src="img/example8.png" class="example" alt="CSS margin example">


<!-- 4. PADDING -->
<h3 id="padding">padding</h3>

<p><b>English:</b> Space inside an element.</p>
<p><b>Español:</b> Espacio interno del elemento.</p>

<pre><code>div {
  padding: 10px;
}
</code></pre>

<img src="img/example9.png" class="example" alt="CSS padding example">


<!-- 5. BORDER -->
<h3 id="border">border</h3>

<p><b>English:</b> Adds a border around an element.</p>
<p><b>Español:</b> Añade un borde alrededor del elemento.</p>

<pre><code>div {
  border: 2px solid black;
}
</code></pre>

<img src="img/example10.png" class="example" alt="CSS border example">


<p><a href="#top">Back to top / Volver arriba</a></p>

</main>

<footer>
    <p>Web4U © 2025</p>
</footer>

</body>
</html>
  

  /*svg.html*/
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Web4U – SVG Tags</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="css/print.css" media="print">
</head>

<body>

<header>
    <h1>SVG Tag Tutorials</h1>
</header>

<nav>
    <a href="index.html" title="Home page">Home</a>
    <a href="html.html" title="HTML tutorials">HTML</a>
    <a href="css.html" title="CSS tutorials">CSS</a>
    <a href="svg.html" class="active" title="You are here: SVG tutorials">SVG</a>
</nav>

<main>

<h2 id="top">SVG Tags – English / Español</h2>
<p><a href="pdf/svg.pdf">Download PDF</a></p>

<div class="toc">
    <ul>
        <li><a href="#svg-tag">&lt;svg&gt;</a></li>
        <li><a href="#rect-tag">&lt;rect&gt;</a></li>
        <li><a href="#circle-tag">&lt;circle&gt;</a></li>
        <li><a href="#line-tag">&lt;line&gt;</a></li>
        <li><a href="#text-tag">&lt;text&gt;</a></li>
    </ul>
</div>


<!-- 1. SVG ROOT -->
<h3 id="svg-tag">&lt;svg&gt;</h3>

<p><b>English:</b> The root SVG container.</p>
<p><b>Español:</b> El contenedor raíz SVG.</p>

<pre><code>&lt;svg width="100" height="100"&gt;&lt;/svg&gt;
</code></pre>

<img src="img/example11.png" class="example" alt="SVG container example">


<!-- 2. RECT -->
<h3 id="rect-tag">&lt;rect&gt;</h3>

<p><b>English:</b> Draws a rectangle.</p>
<p><b>Español:</b> Dibuja un rectángulo.</p>

<pre><code>&lt;rect x="10" y="10" width="80" height="50" fill="blue"&gt;&lt;/rect&gt;
</code></pre>

<img src="img/example12.png" class="example" alt="SVG rect example">


<!-- 3. CIRCLE -->
<h3 id="circle-tag">&lt;circle&gt;</h3>

<p><b>English:</b> Draws a circle.</p>
<p><b>Español:</b> Dibuja un círculo.</p>

<pre><code>&lt;circle cx="50" cy="50" r="40" fill="red"&gt;&lt;/circle&gt;
</code></pre>

<img src="img/example13.png" class="example" alt="SVG circle example">


<!-- 4. LINE -->
<h3 id="line-tag">&lt;line&gt;</h3>

<p><b>English:</b> Draws a straight line.</p>
<p><b>Español:</b> Dibuja una línea recta.</p>

<pre><code>&lt;line x1="10" y1="10" x2="90" y2="90"
      stroke="black" stroke-width="2"&gt;&lt;/line&gt;
</code></pre>

<img src="img/example14.png" class="example" alt="SVG line example">


<!-- 5. TEXT -->
<h3 id="text-tag">&lt;text&gt;</h3>

<p><b>English:</b> Draws text inside SVG canvas.</p>
<p><b>Español:</b> Dibuja texto dentro del lienzo SVG.</p>

<pre><code>&lt;text x="10" y="50" font-size="20"&gt;Hello SVG&lt;/text&gt;
</code></pre>

<img src="img/example15.png" class="example" alt="SVG text example">

<p><a href="#top">Back to top / Volver arriba</a></p>

</main>

<footer>
    <p>Web4U © 2025</p>
</footer>

</body>
</html>

/* ===========================================================
  (style.css)
   =========================================================== */

/* ---- GLOBAL LAYOUT ---- */
body {
    font-family: Arial, Helvetica, sans-serif;
    background: #f7f9fb;
    margin: 0;
    color: #222;
    line-height: 1.6;
}

/* ---- HEADER ---- */
header {
    background: #003f69;
    color: white;
    padding: 20px;
    text-align: center;
}

header h1 { 
    margin: 0;
    font-size: 2em;
}

header h2 { 
    margin: 5px 0 0 0;
    font-weight: normal;
    font-size: 1.1em;
}

/* ---- NAVIGATION ---- */
nav {
    background: #00558f;
    padding: 10px 20px;
}

nav a {
    color: #cde9ff;
    margin-right: 20px;
    text-decoration: none;
    font-weight: bold;
}

nav a:hover {
    color: white;
}

nav a.active {
    color: #ffffff;
    text-decoration: underline;
}

/* ---- MAIN CONTENT ---- */
main {
    background: white;
    max-width: 900px;
    margin: auto;
    padding: 25px;
    box-shadow: 0 0 8px rgba(0,0,0,0.07);
}

h2, h3 {
    color: #003f69;
}

/* ---- TABLE OF CONTENTS ---- */
.toc {
    background: #e3f2ff;
    border-left: 5px solid #00558f;
    padding: 15px;
    margin: 20px 0;
}

.toc ul {
    margin: 0;
    padding-left: 20px;
}

/* ---- CODE BLOCKS ---- */
pre {
    background: #2d2d2d;
    color: #f8f8f2;
    padding: 12px;
    overflow-x: auto;
    border-radius: 4px;
    font-size: 0.95em;
}

code {
    font-family: Consolas, Menlo, monospace;
}

/* ---- EXAMPLE IMAGES ---- */
img.example {
    width: 100%;
    max-width: 650px;
    display: block;
    border: 1px solid #ddd;
    border-radius: 4px;
    margin: 15px 0;
}

/* ---- FOOTER ---- */
footer {
    background: #003f69;
    text-align: center;
    color: white;
    padding: 15px;
    margin-top: 30px;
    font-size: 0.9em;
}


/* ===========================================================
  (print.css)
   =========================================================== */

   @media print {

    /* Hide navigation and footer in PDF */
    nav, footer {
        display: none;
    }

    /* Expand content for clean PDF layout */
    main {
        max-width: 100%;
        padding: 0;
    }

    /* Ensure images scale properly */
    img {
        max-width: 100%;
        height: auto;
    }

    /* Remove background colors to save ink */
    body,
    main,
    header {
        background: white !important;
        color: black !important;
    }

    /* Avoid page breaks inside code blocks */
    pre, code {
        page-break-inside: avoid;
    }
}

/* img */
/* html */

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>example1 – p tag</title>
<style>
body { font-family: Arial; padding: 40px; }
</style>
</head>
<body>
<p>This is a paragraph generated for example1.</p>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>example2 – img tag</title>
<style>
body { font-family: Arial; padding: 40px; }
.img-box {
    width: 150px;
    height: 100px;
    background: #cce5ff;
    display: flex;
    align-items: center;
    justify-content: center;
}
</style>
</head>
<body>
<div class="img-box">IMAGE</div>
<p>Simulated image placeholder.</p>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>example3 – a tag</title>
<style>
body { font-family: Arial; padding: 40px; }
a { color: blue; font-size: 20px; }
</style>
</head>
<body>
<a href="#">This is a link example</a>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>example4 – table tag</title>
<style>
body { font-family: Arial; padding: 40px; }
table {
    border-collapse: collapse;
    width: 300px;
}
td, th {
    border: 1px solid #333;
    padding: 8px;
}
</style>
</head>
<body>

<table>
<tr><th>Name</th><th>Age</th><th>City</th></tr>
<tr><td>Ana</td><td>22</td><td>Madrid</td></tr>
<tr><td>Luis</td><td>31</td><td>Quito</td></tr>
</table>

</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>example5 – form tag</title>
<style>
body { font-family: Arial; padding: 40px; }
label, input { display:block; margin-bottom:10px; }
</style>
</head>
<body>

<form>
<label>Name:
 <input type="text">
</label>
<button>Submit</button>
</form>

</body>
</html>


/* css */

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>example6 – CSS color</title>
<style>
p { color: red; font-size: 24px; }
body { padding: 40px; font-family: Arial; }
</style>
</head>
<body>

<p>This text is red using CSS color property.</p>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>example7 – CSS margin</title>
<style>
.box {
    background: #cef;
    width: 200px;
    height: 100px;
    margin: 40px;
}
body { padding: 40px; font-family: Arial; }
</style>
</head>
<body>

<div class="box"></div>
<p>The box has margin:40px.</p>

</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>example8 – CSS border</title>
<style>
.box {
    width: 200px;
    height: 100px;
    border: 4px solid #333;
}
body { padding: 40px; font-family: Arial; }
</style>
</head>
<body>

<div class="box"></div>
<p>This box has border:4px solid.</p>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>example9 – CSS flexbox</title>
<style>
.container {
    display: flex;
    gap: 10px;
}
.box {
    background: #cfc;
    width: 80px;
    height: 80px;
}
body { padding: 40px; font-family: Arial; }
</style>
</head>
<body>

<div class="container">
    <div class="box"></div>
    <div class="box"></div>
    <div class="box"></div>
</div>

<p>Flexbox row layout.</p>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>example10 – CSS grid</title>
<style>
.grid {
    display: grid;
    grid-template-columns: repeat(2, 100px);
    gap: 10px;
}
.item {
    background: #fcc;
    height: 80px;
}
body { padding: 40px; font-family: Arial; }
</style>
</head>
<body>

<div class="grid">
    <div class="item"></div>
    <div class="item"></div>
    <div class="item"></div>
    <div class="item"></div>
</div>

</body>
</html>


/* SVG */

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>example11 – SVG circle</title>
</head>
<body style="padding:40px; font-family:Arial;">

<svg width="200" height="200">
    <circle cx="100" cy="100" r="80" fill="skyblue"/>
</svg>

</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>example12 – SVG rectangle</title>
</head>
<body style="padding:40px; font-family:Arial;">

<svg width="200" height="140">
    <rect width="180" height="100" x="10" y="10" fill="orange"/>
</svg>

</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>example13 – SVG line</title>
</head>
<body style="padding:40px; font-family:Arial;">

<svg width="200" height="200">
    <line x1="20" y1="180" x2="180" y2="20" stroke="red" stroke-width="4"/>
</svg>

</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>example14 – SVG polyline</title>
</head>
<body style="padding:40px; font-family:Arial;">

<svg width="300" height="200">
    <polyline points="10,150 60,50 120,150 180,50 240,150"
              fill="none" stroke="blue" stroke-width="4"/>
</svg>

</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>example15 – SVG text</title>
</head>
<body style="padding:40px; font-family:Arial;">

<svg width="300" height="120">
    <text x="20" y="60" fill="purple" font-size="32">SVG Text Example</text>
</svg>

</body>
</html>


/* PDF */

/* html.pdf */

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>HTML Tags – PDF Version</title>
<link rel="stylesheet" href="css/style.css">
<link rel="stylesheet" href="css/print.css" media="print">
</head>
<body>

<header>
<h1>Web4U – HTML Tags</h1>
</header>

<main>
<h2>HTML Tags – PDF Version</h2>

<h3>1. &lt;p&gt; – Paragraph</h3>
<p>Defines a paragraph of text.  
Define un párrafo de texto.</p>

<pre><code>&lt;p&gt;This is a paragraph.&lt;/p&gt;</code></pre>

<hr>

<h3>2. &lt;img&gt; – Image</h3>
<p>Embeds an image in the document.  
Inserta una imagen en el documento.</p>

<pre><code>&lt;img src="example.png" alt="demo"&gt;</code></pre>

<hr>

<h3>3. &lt;a&gt; – Link</h3>
<p>Creates a hyperlink.  
Crea un enlace.</p>

<pre><code>&lt;a href="#"&gt;Click me&lt;/a&gt;</code></pre>

<hr>

<h3>4. &lt;table&gt; – Table</h3>
<p>Defines a table structure.  
Define una tabla.</p>

<hr>

<h3>5. &lt;form&gt; – Form</h3>
<p>Allows user input.  
Permite introducir datos.</p>

</main>

</body>
</html>

/* css.pdf */

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>CSS Properties – PDF Version</title>
<link rel="stylesheet" href="css/style.css">
<link rel="stylesheet" href="css/print.css" media="print">
</head>
<body>

<header>
<h1>Web4U – CSS Properties</h1>
</header>

<main>

<h2>CSS Properties – PDF Version</h2>

<h3>1. color</h3>
<p>Changes the text color.  
Cambia el color del texto.</p>

<pre><code>p { color: red; }</code></pre>

<hr>

<h3>2. margin</h3>
<p>Controls space outside an element.  
Controla el espacio exterior.</p>

<pre><code>.box { margin: 40px; }</code></pre>

<hr>

<h3>3. border</h3>
<p>Sets borders of an element.  
Establece bordes.</p>

<pre><code>.box { border: 2px solid black; }</code></pre>

<hr>

<h3>4. display: flex</h3>
<p>Creates a flexible layout.  
Crea un diseño flexible.</p>

<pre><code>.container { display: flex; }</code></pre>

<hr>

<h3>5. display: grid</h3>
<p>Creates a grid layout.  
Crea un diseño de cuadrícula.</p>

<pre><code>.grid { display: grid; }</code></pre>

</main>

</body>
</html>

/* svg.pdf */
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>SVG Tags – PDF Version</title>
<link rel="stylesheet" href="css/style.css">
<link rel="stylesheet" href="css/print.css" media="print">
</head>
<body>

<header>
<h1>Web4U – SVG Tags</h1>
</header>

<main>

<h2>SVG Tags – PDF Version</h2>

<h3>1. &lt;circle&gt;</h3>
<p>Draws a circle.  
Dibuja un círculo.</p>

<pre><code>&lt;circle cx="50" cy="50" r="40" /&gt;</code></pre>

<hr>

<h3>2. &lt;rect&gt;</h3>
<p>Draws a rectangle.  
Dibuja un rectángulo.</p>

<pre><code>&lt;rect width="100" height="80" /&gt;</code></pre>

<hr>

<h3>3. &lt;line&gt;</h3>
<p>Draws a straight line.  
Dibuja una línea recta.</p>

<pre><code>&lt;line x1="10" y1="10" x2="100" y2="70" /&gt;</code></pre>

<hr>

<h3>4. &lt;polyline&gt;</h3>
<p>Draws a multi-point shape.  
Dibuja una polilínea.</p>

<pre><code>&lt;polyline points="10,90 50,10 90,90" /&gt;</code></pre>

<hr>

<h3>5. &lt;text&gt;</h3>
<p>Displays text inside SVG.  
Muestra texto en SVG.</p>

<pre><code>&lt;text x="20" y="40"&gt;Example&lt;/text&gt;</code></pre>

</main>

</body>
</html>
