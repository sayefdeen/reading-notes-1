[PREVIOUS](https://dinaalsaid.github.io/reading-notes/class-01) &nbsp;[HOME](https://dinaalsaid.github.io/reading-notes/)  &nbsp; [NEXT](https://dinaalsaid.github.io/reading-notes/) 

# Introduction follow up

## HTML text
There are two kinds of markup in HTML:
* structural markup :used for structuring a page **ex:** div, span
* Semantic markup :describes the content**ex:** p, img, header

an element can be both semantic and structural.

text element|tag
-----|-------
headings|`<h1></h1>`
paragraphs|`<p></p>`
bold|`<b></b>`
italic|`<i></i>`
subscript|`<sub></sub>`
superscript|`<sup></sup>`
line break|`<br/>`
horizantal rule|`<hr />`
emphasis|`<em></em>`
strong|`<strong></strong>`
abbreviation|`<abbr></abbr>`
definition|`<dfn></dfn>`
strikethrough|`<s></s>`

## CSS
CSS is used to style the html pages to make them look more attractive.

CSS sees the HTML page as boxes (or elements) and associate rules to these boxes in order to change how they look.
The boxes are targeted using **selectors**, and rules are declared by changing the values of the element **properties**.
![cssintro1](images/Css-intro1.PNG)

there are three ways to apply CSS to an HTML file:

* link using the link tag/element (external)
* write CSS code in a style tag (internal)
* from the style attributes in any element’s tag

Using external CSS stylesheet will give you the advantage of applying the same style to all you website pages, less code to write, and faster site load.

#### CSS selectors 
types of selectors:
* universal: `* {} `
* type: `p, h1, div{} `
* class: `.className1 {} `
* ID: `#IDname1 {} `
* child: `li >a {} `
* descendant: `p a {} `

#### cascading rules
If one element has more than one CSS rule linked to it, the final applied rule is considered by:
* if two selectors are identical the last rules are applied.
* if one selector is more specific than the others its rules are applied. **ex**: `p li` selector is more specific than `li` selector.
* if a rule is followed by `!important` it will be applied.

some rules are inhereted by default some can be forced to be inhereted from a parent element to a child element.
