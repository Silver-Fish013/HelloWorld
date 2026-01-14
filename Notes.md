We just writin in this bitch
Anyways I should take notes lol

ELEMENTS!!! RAHHHHHHHH
Elements in HTML look like: 
<tagname> placeholder text </tagname>

some examples are:
<!-- 
<html></html> 
<p></p> 
<body></body> 
<h1></h1> 
-->

eh you get it

Empty HTML ELEMENTS RAAAHAHHHHH
all i got for this part is that they dont need an ending tag <!-- </> this thing -->
EXAMPLE!!!!!
<!-- 
<br> this is a line break
<hr> this is a horizontal line
-->

ATTRIBUTES!!!!!!!!
-All TML elements can have attributes
-They provide extra info about the elements
-They're always specified in the START tag
-They usually come in name/value pairs 
EXAMPLEEE
name="value"

The href attribute: 
The <a> tag defines a hyperlink and the href attribute specifies the URL of that page
EXAMPLE:
<a href="some link here"> what the link says </a>

The src attribute:
The <img> tag is used to embed an image in an HTML page, the src attribute specifies the where the image is coming from
EXAMPLE
<img src="The terrible (1).jpg"> 
HOWEVER theres two differnt ways to specify the URL 
1. The absolute URL: src="SomeWebsite/images/The Terrible (1).jpg"
2. The relative URL: Current page - src="The Terrible (1).jpg" Relative to the domain - src="/images/The Terrible (1).jpg"

Width and Height attributes:
The <img> tag should also contain the width and height attributes, these specifiy the width and height of the image in pixels
EXAMPLE
<img src="The terrible (1).jpg" width="500" height="600">

Alt Attribute
This can be used as the alternate text for an image. Typically used for readaloud settings. It also could appear if the image itself doesn't load.
EXAMPLE
<img src="The terrible (1).jpg" alt="The Terrible can be described as a cursed cat image that looks like a cat with arms and legs and a very detailed face with glowing eyes">

Style attribute
Used to add colors, different fonts, and size
EXAMPLE
<p style="color:red;"> This is a red paragraph </p>

Lang attribute
always included in the <html> tag and declares the language of the Web page
EXAMPLE (but in english mwehehehe)
<html lang="en">
<body>
stuff here
</body>
</html>
Country codes can also be added to the lang attribute
EXAMPLE (with canada bc fuck the US)
<html lang="en-CA">
<body>
stuf here
</body>
</html>

Title attribute
defines extra info about an element
EXAMPLE
<p title="This is a title"> this a paragraph </p>

SUGGESTIONS ON ATTRIBUTES
HTML standard doesn't require only lowercase but it is recommended to get used to in case you use XHTML
HTML standard also does not require quotations for attribute values but again its good practice for other parts of coding. AGAIN XHTML demands quotations so its just better to use them in regular HTML. 
EXAMPLE OF ATTRIBUTE WITHOUT QUOTATIONS THAT XHTML WONT LIKE
<a href=https://www.youtube.com>Lookie it's youtube</a>
Sometimes you HAVE to use quotations on an attribute.
EXAMPLE OF ATTRIBUTE THAT WONT WORK WITHOUT QUOTATIONS
<p title=bingus bongus>

Single and Double quotes
They can be interchanged, its honestly up to you. Only rule with them that i'm seeing is that you cant use the same the same quotation in an attribute id the attribute value itself has quotations. You have to use both in that situation, whatever quotes you use to start the attribute you use the oher for the attribute value itself.
EXAMPLE BC THAT SHIT IS CONFUSING
<p title='The "Fuckin" Terrible'></p>
or the opposite of that
<p title="The 'Fuckin' Terrible"></p>
pretty much that for any attribute that has quotations in it

SUMMARY OF ATTRIBUTES
-All HTML elements can have attributes
-href specifies the URL of the page a link goes to for the element <a>
-src specifies the path of an image to be displayed for the element <img>
-width and height also are used for the element <img> to provide size info about an image
-alt is ALSO used for <img> element and provides an alternate text for an image
-style is used to add color, font size, and more to an element
-lang is used in <html> and declares the language of a webpage
-title defines extra info of an element

HEADINGS!!!!!!
Them bitches the titles or subtitles you want displayin on the webpage
They're defined using the <h1> to <h6> tags
<h1> is the biggest setting and is usually used as the most important heading
<h6> is the smallest and usually used as the least imporatnt heading
People usually skin through awebpage by it's headings so its usually used as a way to structure the page.
APPARENTLY people like to follow a VERY SPECIFIC way to format the headings and follow specific rules.
EXAMPLE OF THE DUMB DUMB
<h1> - page title
<h2> - section titles
<h3> - sub-sections
To get bigger headings you can use the style attribute and use the font-size property
EXAMPLE OF THE BIGGHEADING CODE
<h1 style="font-size:60px;"> Big Heading </h1>

PARAGRAPHS!!!!!!
the <p> element defines a paragraph
These always start on a new line and browsers usually add a margin before and after a paragraph
EXAMPLE OF THE PARARAPHS
<p>This a mf paragraph</p>
<p>This another mf paragraph</p>

HTML Display
You cant be sure how the HTML will be displayed due to resizing of screens.
Adding extra lines or spaces in the code does not add space on the display, the browser will just remove any spaces and lines.
EXAMPLE OF SPACES AND LINES IN PARAGRAPHS
<p>
This a paragraph
but it contains a shitton of lines
like this
in the source code
but the browser says
FUCK YOU 
and ignores it
</p>

<p> This is a 
    paragraph that has      a lot
of      spaces but the  browser     
            ignores it
</p>

HTML Horizontal Rules
<hr> defines a horizontal rule which is a blank break in between paragrahs
EXAMPLE
<h1>This Bitch a Heading</h1>
<p>This bitch some text</p>
<hr> <!--This bitch leaves a space between paragraphs or any content-->
<h2>This Bitch Some OTHER Heading</h2>
<p>This bitch some more text</p>
<hr> <!--This bitch still leavin space like some kinda praise kink bastard-->
its an empty tag so this mofo never ends, lol jk you just dont need an ending tag

HTML Line Breaks
<br> defines a LINE break, it actually reads on the webpage as a break in the paragraph.
EXAMPLE
<p>THIS BITCH<br>BREAKS<br>THE LINE IN THE PARAGRAPH</p>
this mofo ALSO doesnt need an ending tag bc it has an ego and thinks its too good for one

HTML <pre> ELEMENT
<pre> defines preformatted text that usually shows up as courier font and preserves both spaces and line breaks.
EXAMPLE
<pre>
This a poem

I suck at poems

I like poems tho

End of poem
</pre>
