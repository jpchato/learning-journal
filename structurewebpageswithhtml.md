# **Structuring Web Pages with HTML**
* Understand the target audience
    * age range, men or women, country, urban or rural, income, education, etc
    * individuals or companies
* Why will people visit website?
    * Understand peoples **motivations** and **goals** for visiting your website
* What are people trying to achieve?
* What information do visitors need?
    * Offer key information and some additional supporting information that might be useful
* How often will people visit the site?
    * How often people visit can determine how often it needs to get updated.  
    * For example, a news website probably gets updated every day
* Site Maps
    * Once you know what needs to go on the page, you can begin to organize it
    * Site Map= a diagram of pages that shows structure of the site
    * Card Sorting= Placing information that visitors might need to know on separate pieces of paper and organizing them into groups
* Wireframes
    * A  sketch of important information that needs to go on each page of a site
    * Shows hierarchy of info
    * Wireframes help ensure that all necessary info for a page is included
    * **DO NOT** include color scheme, font choices, backgrounds, or images for wireframe
    * Function, not form is key at this stage
*  Getting Your Message Across Using Design
    * Goal of visual design is to communicate
    * Organization of information on a webpage helps user identify what is important
    * Content
        * Webpages have lots of info to share.  Important to **prioritize** and **organize** the info
    * Prioritizing
        * Draw attention to or away from certain pieces of content by making them **distinct**
        * Designers use **visual hierarchy** to help users focus on what's important
    * Organizing
        * **Grouping** related content into **blocks** or **chunks** simplifies the page
        * Use **similar** visual style for certain types of information to help users associate that style with a certain type of content
* Visual Hierarchy
    * Use contrast to create a visual hierarchy that gets your key message across
    * Size
        * Larger elements grab users' attention
    * Color
        * Colors can draw attention, especially brighter colors
    * Style
        * Different style from background will draw attention
* Grouping and Similarity
    * Proximity
        * Items place close together are perceived to be related
    * Closure
        * Complicated arrangements promp readers to create real or imaginary boxes around elements
    * Continuance
        * Items placed in a line or curve are perceived to be related
    * White Space
        * Less white space between items=more related and vice versa
    * Color
        * Background colors behind items can emphasize their connection
    * Borders    
        * Boxes things together
* Designing Navigation
    * Helps people find where they want to go and helps them understand how site is organized
    * Components of good navigation:
        * Concise
            * No more than eight links
        * Clear
            * Single descriptive words for each link
        * Selective
            * Should reflect sections or content of site (no log in, legal, or search info)
        * Context
            * Let user know where they are in the website
            * Use a different color scheme or visual to indicate where nav is
        * Interactive
            * Link should be big enough to click on and visually distinct from other content on the page
        * Consistent
            * Primary navigation should remain the same
## Summary
* Understand who audience is, why they're visiting the site, what info they want, and when they are likely to return
* Site maps allow designers to plan site structure
* Wireframes organize the info that will go on each web page
* Design is communication. Visual hierarchy helps express what you are trying to say
* Color, size, and style help make information distinct
* Grouping and similarity help simplify the info being presented

# **Structure**
* HTML describes the structure of a web page
* Looking at how other sites are built
    * Right click>view source
* HTML pages are text documents
* HTML tags give information they wrap special meaning
* Tags=elements
* Tags *usually* come in pairs. Don't forget to close tags

# **HTML5 Layout**
* div is being replaced by more expressive terms such as header, page, article, paragraph, footer, etc
* List of HTML5 tags:
    * header, footer, nav, article,aside, section, hgroup, figure, figcaption, div
* HTML5 elements indicate the purpose of different parts of a web page as opposed to div
* Older browsers do not understand HTML5. They need to be told which elements are block-level elements
* Extra JavaScript is needed for HTML5 work in IE8

# **Extra Markup**
* Several different versions of HTML have been used since the creation of the web (HTML 4, XHTML 1.0)
* Add comments to code so when you come back to it later the code can make sense
* Comments are not viewable on the web page, but they are viewable in the source code
* ID Attribute
    * Used to uniquely identify a specific element from other elements on the page
    * No two elements on the same page should have the same value for their id attributes (because then they would no longer be unique)
    * Giving an element a unique identity allows you to style it differently from other instances of the same element on the page
    * id attribute is known as the **global attribute** because it can be used on any element
* Class Attribute
    * When you want to identify several elements as being different from other elements on the page
    * Class attributes can be shared unlike ID attributes
* Block Elements
    * **Block level** elements always start on a new line in the browser (h1, p, ul, li)
* Inline Elements 
    * **Inline elements** continue on the same line as their neighboring elements (a, b, em, img)
* Grouping Text and Elements in a Block
    * div allows a set of elements to be grouped together in one block
    * The contents of a div element will start on a new line in the browser
    * Using an id or class attribute on the div element allows for CSS style rules to manipulate the amount of space that the div element occupies and can change the appearance of the elements contained within it
* Grouping Text and Elements Inline
    * span acts like an inline equivalent of div
    * It can be used to contain a piece of text where there is no other alternative element to help differentiate it from surrounding text
    * It can contain multiple inline elements
    * Mostly used in conjunction with CSS  to control the appearance of the elements within
* Iframes
    * An abbreviation of inline frame
    * Used to place a window in the webpage
    * src attribute specifies the url of the page to show in the frame
    * height attribute specifies the heigh of the frame
    * width attribute specifies the width
    * seamless is used when scrollbars are not needed
* Information About Your Pages
    * meta
        * The meta element lives in the head element and contains info about the webpage
        * Not visible to user but fulfills multiple purposes such as telling search engines about the page, who created it, and if it's time sensistive
        * An empty element that does not have a closing tag
        * Uses attributes to carry info
        * Name and attribute are the most common attributes in the meta tag
        * Some defined values for the name attribute: description, keywords, robots

