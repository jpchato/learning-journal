# **CSS**
* CSS=Cascading style sheet
* All rules are cascaing. HTML reads css rules from top to bottom
* A way to visually style html
* p{font-family:Arial;}
    * p=selector
    * font-family: Arial; = delcaration
    * font-family=property
    * Arial= value
* CSS works off the idea that there is an invisible box around every element of HTML
    * CSS creates rules that dictate how each box should look
* External CSS
    * link element is used to tell browser where to find CSS file for styling the page
    * href= path to css file
    * type=document type to be linked to
    * rel=Identified relationship between html page and the file it's linked to.  Value should be style sheet when linking to css files
* Internal CSS
    * style tag
    *  usually sits inside the head element of the page
    * style uses type attribute to specify the styles to be used
* CSS font rules are inherited from parent element unless specified otherwise. Background and color rules are not inherited

## <span style="color:blue">**Color**
* Foreground Color
    * color property allows user to choose the color of the text within an element
    * rgb values
        * Use leves of red, green, blue between to create colors i.e. rgb (1, 2, 3)
    * Hex codes
        * Six digit code that represents amount of red, green, and blue i.e. #ee3e80
    * Color names
        * 147 predefined color names.  i.e. red, green, blue, yellow, purple, etc.
* Background Color
    * Uses rgb, hex, and color
    * Used to set background color of each html box
    * If no color is specified, background is transparent
* Understanding Color
    * Colors are a mix of rgb
    * Screens mix these colors to create different colors
    * saturation
        * refers to the amount of gray in a color
        * at max, mostly no gray
        * at min, mostly gray
    * brightness
        * how much black is in a color
        * max bright=no black
        * min bright=dark
* Contrast
    * Foreground and background colors should have enough contrast for text to be readable
    * Text is hard to read with low contrast
    * Text is easy to read with high contrast
    * Long spans of text should use medium contrast to reduce eye strain
* Opacity
    * Level of "see-throughness"
    * 0-1 to indiciate 0%-100%
    * Might not work in older browsers
### <span style="color:red">Color Summary
* Color conveys mood, creates reactions, and brings site to life
* Three ways to specify colors: 1) rgb values 2) hex codes 3) color names
* Make sure to have enough contrast between text and background color
* 


