I will write down the CSS and HTML I want to remember here, and merge it with my dictionary file when ready

------------------------------------------------------------------------

<h2> HTML, CSS </h2>

------------------------------------------------------------------------


<h3> GENERAL CSS </h3>

- **color** ——> (red, green)

- **background-color** ——> (silver, red)

- **background-image** ——> url(urlhere.png);

- **background-position** ——>

- **background-repeat** ——> (repeat-x)

- **background-attachment** ——> (fixed)

- **font-family** ——> (ariel, serif) Can import new fonts using google fonts or other, using < link > tag.

- **font-weight** ——> (normal, bold, lighter, bolder, 100, 900) Sets boldness of font

- **font-style** ——> (normal, italic, oblique, etc)

- **font-size** ——> (15px)

- **text-decoration** ——>

- **text-transform** ——>

- **text-align** ——> (right, left, center, justify)

- **width and height** ——> (20px, 30%)

- **padding**  ——>  “…controls the amount of space between an elements content and its border.” Ex of close wise notation: padding: 20px 40px 30px 10px;. Starts at top and ends at left

- **padding-right, padding-left, padding-top, padding-bottom** ——> 

- **border**  ——>  “…controls the amount of space between an element’s border and its surrounding elements”

- **margin**  ——>  “…controls the amount of space between and element’s border and surrounding elements.” A negative margin will make the element become larger. Ex of close wise notation: margin: 20px 40px 30px 10px;. Starts at top and ends at left

- **margin-right, margin-left, margin-top, margin-bottom** ——> 

- **!important**  ——>  Makes sure that that css property overrides all other properties. (color: pink !important;)

- **--(name)=“example”**  ——>  creates a CSS variable. Reference example after creation: (background-color: var(—example-variable, fallback-value))

- **transform** ——>

<h3> Misc values </h3>
  
- **em** - stands for elastic width, and it is a relative unit of measurement. 

- **vh/vw** - stands for viewport height and viewport width. Used to set height and width in CSS

- **px** - Stands for pixels

- **%** - Sometimes percentages can be used

<h3> LISTS </h3>

- **list-style-type** ——> Values include: none, disc, decimal, circle, square, kannada, korean-hangul-formal, and many more. All values: (https://developer.mozilla.org/en-US/docs/Web/CSS/list-style-type) 

- **list-style** ——>

<h3> CSS BORDERS </h3>

- **border** ——>

- **border-color** ——> (red)

- **border-width** ——> (5px)

- **border-style** ——> (solid)

- **border-radius** -——> (10px, 50% - makes a circle, )

<h3> STYLE BASED ON STATE </h3>

- **a:link** ——>

- **a:visited** ——>

- **a:hover** ——>

<h3> FUNCTIONS </h3>

- **calc()** ——>

- **rotate([0-1]turn)** ——> Used with transform

<h4> Filters </h4>

- filter: opacity()

- filter: brightness()

- filter: contrast()

- filter: grayscale()

- filter: drop-shadow()

- filter: blur()

- filter: url()

- filter: hue-rotate()

- filter: saturate()

- filter: invert()

<h3> @rules </h3>

- **@import ‘stylesheetname’;** ——> imports a stylesheet into another stylesheet

- **@media** ——> “Imports media queries, which use conditional logic for applying CSS styling”. For instance, @media (min-width: 25em) { … }, which applies the CSS in the curly brackets if the viewport is wider than 25em

<h3> HTML Tags </h3>

- **< h1 >-< h6 >** ——> Called a header. Contains machine-readable information / metadata about a document, like title, script, and style sheets
  
- **< div >** ——> Only used for semantics. Use for block level semantics

- **< span >** ——> Only semantic use, it is in-line which is different from < div > which is used for block semantics.

- **< p >** ——> Used to make paragraphs. Called a paragraph tag. 
  
- **< head >** ——> Is the area where metadata is put, always goes after the < html > tag. 
  
- **< body >** ——> The content of the HTML document goes inside
  
- **< script >** ——> JavaScript can be run inbetween the < script > tag.
  
- **< html >** ——> Used to designate where html runs in a file. 
  
- **< style >** -——> Contains style/css information for a document

- **< ul >** ——> Unordered lists. Used for when order of elements does not matter, like a shopping list
  
- **< ol >** ——> Ordered lists. Used for where order of elements does matter, like a recipe
  
- **< li >** ——> List item. 
  
- **< a >** ——> Anchor tag. Used to link to other files / webpages. 

- **< img >** ——> Used to add images. Attributes are src, alt, 

- **< iframe >** ——> Allows a website to run inside of your website. 

- **< link >** ——> Used to link different files together, like an html file with your css and .js files. Also useful for adding in things from open source websites, like transparent-textures. 

- **< strong >** ——> Creates bold text. 

- **< title >** ——> This displays a name in the tab of the webpage in your browser, and is also use for search engine results

- **< main >** ——> Semantic use: designate where the main content in your file is.

- **< footer >** ——> Semantic use: designate where the footer content of your website is.

- **< header >** ——> Semantic use: designare where the header content of website is.

- **< nav >** ——> Used to designate the area where a navigation is made.

- **< video >** ——>

- **< article >** ——> 

- **< section >** ——> Semantic use: creates sections in code

- **< input >** ——> Attributes are placeholder, required, type 

- **< form >** ——> Used to web build forms that submit data to a web server. Attributes are action, 

- **< button >** ——> Adds a button. Attributes are submit, 

- **< label >** ——> 

- **< main >** ——> Represents dominant content in body

- **< section >** ——> Represents a standalone section in a website

- **< table >** ——> Used to make a table

- **< tr >** ——> Table row

- **< th >** ——> Table header

- **< em >** ——> Emphasis, creates italicized text

- **< br/ >** ——> Creates a breakline in text

- **< hr/ >** ——> Creates a horizontal line for thematic purposes

- **< sub >** ———> Creates subscript

- **< sup >** ———> Creates superscript

<h3> HTML Attributes </h3>

- **src** ——> Used inside of < img > tags to imbed an image URL. 

- **alt** ——> Used inside of tags that have images. If the image does not load properly, the text appears. Also used for those who have vision problems. All image elements must have an alt attribute.

- **href** ——> Used inside of < a > tags to add links. For example: < a href = “example.com” >text< /a >. It contains URL address of a link. 

- **target** ——> An anchor tag attribute specifies where to open a link. The value “_blank” specifies to open a link to a new tab. 

- **type** ——> Used in input tags to specific what kind of input. Values are text, 

- **placeholder** ——> Used for input tag. What is displayed in an input element before user has inputted anything.

- **action** ——> Used in form tag. The value that action holds is where the value inside of the form tags is sent to. 

- **submit** ——-> Used in button tag. It allows data to be sent from a form to a url when the button is clicked. 

- **required** ——> Makes specific forms required so user cannot submit them until they are filled out. 

- **radio** ——> 

- **id** ——> Used to style a single element in CSS

- **class** ——> Used to style multiple elements in CSS. Refers to using .(name) notation

<h3> Misc HTML </h3>

- **Comments** ——> Start a comment with <!— and end that comment with —>
