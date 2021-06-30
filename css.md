# CSS Reading Notes

### What is CSS?
CSS stands for Cascading Style Sheets. It's a language used for altering how webpages created with HTML look to the end-user.

### How does CSS work?
- CSS is a rule-based language.
- CSS opens with a selector, which selects the HTML element to style
- Next you used `{}` to insert declarations which take the form of property and value pairs. 
- CSS is organized into modules.
- A browser will format the HTML code according to the information in the style sheet

### External CSS
An external style sheet can change the look of a website by changing just one file. Each HTML page includes a reference to the external sheet inside a link element, which is inside the head section. It can be written in any text editor, and must be saved with a .css extension.

### Internal CSS
You can use an internal style sheet if one HTML page has a unique style. This is defined inside the style element which is inside the head section.

### Inline CSS
Inline CSS can be used to apply style to a single element.

### Cascading Order
1. Inline style (inside an HTML element)
2. External and internal style sheets (in the head section)
3. Browser default

### CSS Color
Color defines the text color. In order to change background or other colors, you need to specify background-color etc. You can use rgb, rgba, hsla, and hex codes to change colors.



[<--HOME](https://erinsp.github.io/reading-notes/)