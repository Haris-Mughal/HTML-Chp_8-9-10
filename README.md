# HTML-Chp_8-9-10

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
    #body {
    display: flex;
} 
    </style>
</head>
<body>
    <header>
        <nav>
            <a href="index.html">Home</a> |
            <a href="extra-markup.html">Extra Markup</a> |
            <a href="matadata.html">Matadata</a>
        </nav>
        <h1 style="text-align:center">Structure</h1>
<h2>Points about this:</h2>
<p>The things which read in this chapter to understand and overview of HTML.</p>
<br />
    </header>

   <main>
<h3>1- Comment : </h3>
<p>comment is written as : " &lt;!-- --&gt; "</p>
<h3>2- Imp Tags : </h3>
<p>In newspaper, books and forming blocks..</p>
<ul>
    <li><code>&lt;section&gt;</code>Tag</li>
    <li><code>&lt;article&gt;</code>Tag</li>
    <li><code>&lt;aside&gt;</code>Tag</li>
</ul>
<p>&emsp;are used.</p>
<h3>3- Content Division : </h3>
<p>jab kisi content (line-this is a "book") ka darmian ma khuch styling krni ho to &lt;span&gt; tag lgta ha.</p>
<h4>Example : </h4>
<p>This is a <span style="color:green;">BOOK</span></p>
<h3>4- Style : </h3>
<p>It is used to styling by targeting (in CSS) at "internalCSS (head portion)" , "externalCSS (style sheet)" , "inlineCSS (between line)" .</p>
<h4>Example : </h4>
<h5>1- Internal CSS</h5>
<p>This is a <span class="book">BOOK</span></p>
<style>
    .book {
        color: green;
    }
</style>
<br />
<h5>2- External CSS</h5>
<p>This is a <span id="boook">BOOK</span></p>
<p><small>it is styled in styling sheet.</small></p>
<style>
    #boook {
        color: green;
    }
</style>
<br />
<h5>3-Iinline CSS</h5>
<p>This is a <span style="color: green;">BOOK</span></p>
<h3>5- Remove Underline : </h3>
<p>To remove underline from link..." Text-decoration:none; " is used.</p>
<h4>Example : </h4>
<p><a href="book" style="text-decoration:none;">Book</a></p>
</main><br /><br />
    <footer>
<p>&copy; 2022. All Rights Reserved.</p>
    </footer>

</body>
</html>
