## Lists & Links - HTML

1.  There are three main types of lists in HTML: ordered, unordered, and definition. What are their differences?
* Ordered Lists: lists where each item is numbered
* Unordered Lists: lists that begin with a bullet point
* Definition Lists: made up of a set of terms along with definitions for each term

2.  What is the basic structure of an element used to link to another website?
* Links are created using the <a> element. The clickable portion is anything between the opening tag and closing tag. You specify the URL by using the href attribute within the opening tag.

3.  What attribute should you include in a link to open a new tab when the link is clicked?
* You would use the target attribute to specify that a URl should open in a new tab.

4.  How do you link to a specific part of the same page?
* You can use ID attributes within the <a> tags where the href would normally go


## CSS

1.  What is the purpose of CSS?
* CSS gives a webpage its design - color, font type, etc.

2.  What does CSS stand for? What does cascading mean in this case?
* Cascading Style Sheets. The cascade refers to the fact that if there are two or more rules that apply to the same element the latter rule will take precedence if they're targeting the same element. If one is more specific than the others then it will take precedence.

3.  What is the basic structure of a CSS rule?
* A CSS rule contains two parts, a selector and a declaration. Selectors indicate the element the rule applies to, and the declaration indicates how the elements should be styled.

4.  How do you link a CSS stylesheet to your HTML document?
* You can use the link element in an HTML doc to tell the browser where to find the CSS file to style the page.

5.  When is it useful to use external stylesheets as opposed to using interal CSS?
* If you have a site with more than one page it'll be better to use an external CSS file. This will allow all pages to use the same style rules rather than needing to repeat them on each page. Plus it looks cleaner.

6.  Describe what a color hex code is.
* Six-digit code that represent the amount of red, green, and blue in a color preceded by a pound sign.

7.  What are the three parts of an HSL color property?
* Hue, saturation, and lightness. It's an alternative way to specify color.

8.  In the world of typeface, what are the three main categories of fonts? What are the differences between them?
* Serif: extra details on the ends of the main letter strokes. Considered easier to read for blocks of Text
* Sans-Serif: fonts which have straight ends to letters and much cleaner design. If text is small easier to read
* Monospace: every letter is the same width. Good for code

9.  When specifiying font-size, what are the main three units used?
* The three units used are pixels, percentages, and EMS (width of letter M)
