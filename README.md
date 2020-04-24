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
        
#HTML Buttons
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
    
# The HTML <head> Element
    The HTML <head> element is a container for metadata. HTML metadata is data about the HTML document. Metadata is not displayed.
    The <head> element is placed between the <html> tag and the <body> tag:


    
    
