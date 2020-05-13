# Learn-HTML
# HTML Tags
 HTML tags are element names surrounded by angle brackets:
    <tagname>content goes here...</tagname>
        HTML tags normally come in pairs like <p> and </p>
        The first tag in a pair is the start tag, the second tag is the end tag
        The end tag is written like the start tag, but with a forward slash inserted before the tag name

# The <!DOCTYPE> Declaration
    The <!DOCTYPE> declaration represents the document type, and helps browsers to display web pages correctly.
    It must only appear once, at the top of the page (before any HTML tags).
    The <!DOCTYPE> declaration is not case sensitive.
    The <!DOCTYPE> declaration for HTML5 is:
       <!DOCTYPE html>
    
# HTML Basic Examples
    All HTML documents must start with a document type declaration: <!DOCTYPE html>.
    The HTML document itself begins with <html> and ends with </html>.
    The visible part of the HTML document is between <body> and </body>.
    EXAMPLE:
        <!DOCTYPE html>
        <html> <body>
        <h1>My First Heading</h1>       //heading
        <p>My first paragraph.</p>      //paragraph
        </body> </html>

# HTML Headings
    HTML headings are defined with the <h1> to <h6> tags.
    <h1> defines the most important heading. <h6> defines the least important heading.
    
# HTML Paragraphs
    HTML paragraphs are defined with the <p> tag:
    EXAMPLE:
        <p>This is a paragraph.</p>
        <p>This is another paragraph.</p>
        
# HTML Links
    HTML links are defined with the <a> tag:
    Example
        <a href="https://www.w3schools.com">This is a link</a>      //here 'This is a link' will be visible in the page.
            The link's destination is specified in the href attribute. 
            Attributes are used to provide additional information about HTML elements.
# HTML Images
    HTML images are defined with the <img> tag.
    The source file (src), alternative text (alt), width, and height are provided as attributes:
    Example
        <img src="Image Link/adress" alt="alternative text" width="104" height="142">
        
# HTML Buttons
    HTML buttons are defined with the <button> tag:
    Example
        <button>Click me</button>
        
# HTML Lists
    HTML lists are defined with the <ul> (unordered/bullet list) or the <ol> (ordered/numbered list) tag, followed by <li> tags (list items):
    Example:
        <ul> <li>Coffee</li> <li>Tea</li> <li>Milk</li> </ul>       //This is unordered list
        <ol> <li>Coffee</li> <li>Tea</li> <li>Milk</li> </ol>       //This is ordered list
        
# HTML Elements
    An HTML element usually consists of a start tag and an end tag, with the content inserted in between:
    <tagname>Content goes here...</tagname>
    HTML elements with no content are called empty elements. Empty elements do not have an end tag, such as the <br> element (which indicates a line break).
    
# HTML Attributes
    All HTML elements can have attributes
    Attributes provide additional information about an element
    Attributes are always specified in the start tag
    Attributes usually come in name/value pairs like: name="value"
    
# The style Attribute
    The style attribute is used to specify the styling of an element, like color, font, size etc.
    Example
        <p style="color:red">This is a red paragraph.</p>
        
# The title Attribute
    Here, a title attribute is added to the <p> element. The value of the title attribute will be displayed as a tooltip when you mouse over the paragraph:
    Example
        <p title="I'm a tooltip"> This is a paragraph. </p>
        
# Bigger Headings
    Each HTML heading has a default size. However, you can specify the size for any heading with the style attribute, using the CSS font-size property:
    Example
        <h1 style="font-size:60px;">Heading 1</h1>

# HTML Horizontal Rules
    The <hr> tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule.
    The <hr> element is used to separate content (or define a change) in an HTML page:
    
# The HTML head Element
    The HTML <head> element is a container for metadata. HTML metadata is data about the HTML document. Metadata is not displayed.
    The <head> element is placed between the <html> tag and the <body> tag:

# The HTML pre Element
    With HTML, you cannot change the output by adding extra spaces or extra lines in your HTML code.
    The HTML <pre> element defines preformatted text.
    The text inside a <pre> element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks:
    
# The HTML Style Attribute
    Setting the style of an HTML element, can be done with the style attribute.
    The HTML style attribute has the following syntax:
    <tagname style="property:value;">

# Background Color
    The CSS background-color property defines the background color for an HTML element.
    This example sets the background color for a page to powderblue:
    Example
        <body style="background-color:powderblue;">
        <h1>This is a heading</h1> <p>This is a paragraph.</p></body>
        
# Fonts
    The CSS font-family property defines the font to be used for an HTML element:
    Example
        <h1 style="font-family:verdana;">This is a heading</h1> <p style="font-family:courier;">This is a paragraph.</p>
        
# Text Alignment
    The CSS text-align property defines the horizontal text alignment for an HTML element:
    Example
        <h1 style="text-align:center;">Centered Heading</h1> <p style="text-align:center;">Centered paragraph.</p>
        
# HTML Formatting Elements
    Formatting elements were designed to display special types of text:
        <b> - Bold text
        <strong> - Important text
        <i> - Italic text
        <em> - Emphasized text
        <mark> - Marked text
        <small> - Small text
        <del> - Deleted text
        <ins> - Inserted text
        <sub> - Subscript text
        <sup> - Superscript text
        
# HTML Quotation and Citation Elements
# HTML 'q' for Short Quotations
    The HTML <q> element defines a short quotation. Browsers usually insert quotation marks around the <q> element.
    Example
        <p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
        
# HTML 'blockquote' for Quotations
    The HTML <blockquote> element defines a section that is quoted from another source. Browsers usually indent <blockquote> elements.

# HTML 'abbr' for Abbreviations
    The HTML <abbr> element defines an abbreviation or an acronym. Marking abbreviations can give useful information to browsers, translation systems and search-engines.
    Example
        <p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>

# HTML 'bdo' for Bi-Directional Override
    The HTML <bdo> element defines bi-directional override. The <bdo> element is used to override the current text direction:
    Example
        <bdo dir="rtl">This text will be written from right to left</bdo>

# HTML Comment Tags
    You can add comments to your HTML source by using the following syntax: 
        <!-- Write your comments here -->
    Notice that there is an exclamation point (!) in the opening tag, but not in the closing tag.
        
# Styling HTML with CSS
    CSS stands for Cascading Style Sheets. CSS describes how HTML elements are to be displayed on screen, paper, or in other media. 
    CSS saves a lot of work. It can control the layout of multiple web pages all at once. CSS can be added to HTML elements in 3 ways:
        Inline - by using the style attribute in HTML elements  
        Internal - by using a <style> element in the <head> section
        External - by using an external CSS file
        
# Internal CSS
    An internal CSS is used to define a style for a single HTML page. An internal CSS is defined in the <head> section of an HTML page, within a <style> element:
    <head><style>body {background-color: powderblue;}
    h1   {color: blue;}
    p    {color: red;}</style></head>
         
# External CSS
    An external style sheet is used to define the style for many HTML pages. With an external style sheet, you can change the look of an entire web site, by changing one file!
    To use an external style sheet, add a link to it in the <head> section of the HTML page:
        <head> <link rel="stylesheet" href="styles.css"> </head>

# CSS Border
    The CSS border property defines a border around an HTML element: Example
    p {border: 1px solid powderblue;}
    
# Chapter Summary
    Use the HTML style attribute for inline styling
    Use the HTML <style> element to define internal CSS
    Use the HTML <link> element to refer to an external CSS file
    Use the HTML <head> element to store <style> and <link> elements
    Use the CSS color property for text colors
    Use the CSS font-family property for text fonts
    Use the CSS font-size property for text sizes
    Use the CSS border property for borders
    Use the CSS padding property for space inside the border
    Use the CSS margin property for space outside the border

# HTML Links - The target Attribute
    The target attribute specifies where to open the linked document. The target attribute can have one of the following values:
    _blank - Opens the linked document in a new window or tab
    _self - Opens the linked document in the same window/tab as it was clicked (this is default)
    _parent - Opens the linked document in the parent frame
    _top - Opens the linked document in the full body of the window
    framename - Opens the linked document in a named frame
    This example will open the linked document in a new browser window/tab: Example
        <a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>
    
# Button as a Link
    To use an HTML button as a link, you have to add some JavaScript code. JavaScript allows you to specify what happens at certain events, such as a click of a button: Example
    <button onclick="document.location = 'default.asp'">HTML Tutorial</button>
    
    
