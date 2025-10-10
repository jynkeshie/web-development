# web-development
learning html
Empty tags in html have no closing tags e.g; <br>, <hr>
A tooltip is  a small pop-up box that appears when a user hovers over an element, providing additional information about that element. You can create tooltips using the title attribute, CSS hover effects, or JavaScript libraries like Bootstrap for more advanced features.

Single/double quotes - Double quotes around attribute values are the most common in HTML, but single quotes can also be used. e.g; <p title='John "ShotGun" Nelson'>, or <p title="John 'ShotGun' Nelson">

<hr> tag defines a thematic break in an HTML page, and is most often displayed as a ***horizontal rule***. The <hr> element is used to separate content (or define a change) in an HTML page

<pre> tag defines preformatted text. The text inside a <pre> element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks.

Formatting elements were designed to display special types of text;
<b> - Bold text
<strong> - Important text (display - bold)
<i> - Italic text
<em> - Emphasized text (display - italics)
<mark> - Marked / highlighted text
<small> - Smaller text
<del> - Deleted text from a document (Browsers will usually strike a line through deleted text)
<ins> - Inserted text into a document (underlined)
<sub> - Subscript text
<sup> - Superscript text

Quotations
<blockquote> - a section that is quoted from another source. Browsers usually indent <blockquote> elements. e.g, <blockquote cite="link">text/paragraph</blockquote>

<q> - short quotation.Browsers normally insert quotation marks around the quotation.

<abbr> - an abbreviation or an acronym, e.g, "CSS", "Mr." Tip: Use the global title attribute to show the description for the abbreviation/acronym when you mouse over the element.( <p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p> )

<address> - the contact information for the author/owner of a document or an article. The contact information can be an email address, URL, physical address, phone number, social media handle, etc. The text in the <address> element usually renders in italic, and browsers will always add a line break before and after the <address> element.

<cite> - title of a creative work, e.g., a book. A person's name is not the title of a work. usually renders in italic.

<bdo> for Bi-Directional Override - overrides the current text direction. e.g right to left (<bdo dir="rtl">This text will be written from right to left</bdo> )

Comments are written as; <!-- Write your comments here -->
Comments are not displayed in the browser, but they can help document your HTML source code. They can place notifications and reminders in your HTML code
Comments can be used to hide content temporarily, even more than one line. Great for debugging HTML, because you can comment out HTML lines of code, one at a time, to search for errors.
they can also be used to hide Inline Content - to hide parts in the middle of the HTML code. (<p>This <!-- great text --> is a paragraph.</p>)

Colors - specified with predefined color names, or with RGB, HEX, HSL, RGBA, or HSLA values.
A Favicon is a small image displayed next to the page tittle in the browser tab. To add a favicon to your website, either save your favicon image to the root directory of your webserver, or create a folder in the root directory called images, and save your favicon image in this folder. A common name for a favicon image is "favicon.ico". Next, add a <link> element to your "index.html" file, after the <title> element.

<title> is shown in the browser's toolbar. It provides a title for the page when it is added to favorites, and displays a title for the page in search engine-results (SEO)

A table in HTML consists of table cells inside rows and columns. Each table cell is defined by a <td></td> tag. (td refers to table data like images, texts, other tables, etc.). Everything between <td> and </td> is the content of a table cell.
tr stands for table row.
If you want your cells to be table header cells, use the <th> (table header) tag instead of the <td> tag. By default, the text in <th> elements are bold and centered, but you can change that with CSS.
<caption> - table caption
<colgroup>- a group of one or more columns in a table for formatting
<col> - column properties for each column within a <colgroup> element
<thead>	Groups the header content in a table
<tbody>	Groups the body content in a table
<tfoot>	Groups the footer content in a table
Table Borders are added using CSS border property on table, th, and td elements. border-collapse: collapse, prevents having double borders.
If you set a background color of each cell, and give the border a white color (the same as the document background), you get the impression of an invisible border. With the border-radius property, the borders get rounded corners. you can also Skip the border around the table by leaving out table from the css selector.
border-styles; dotted, dashed, solid, double, groove, ridge, inset, outset, none, hidden.

ordered lists <ol>, use the HTML "type" attribute to define the numbering type. e.g, type="A" for uppercase letters. you can also use "start="50" to start from a specific number. 
unordered lists <ul>, Use the HTML "list-style-type" attribute to define the numbering type. e.g, list-style-type:circle; (disc - for bullets by default, square,none).

inline elements do not start on a new line.e.g, a, img, button, span - used to mark up a part of a text or a part of a document, cite, code, textarea,..
block elements take full width available. e.g p, div, h1, table, address, article, aside,..