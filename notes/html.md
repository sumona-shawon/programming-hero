### Basics
- html, DOCTYPE, lang, head, title, meta tags body, footer
- element, attribute, semantics, inline, block, div, span, comment + (html5 and html attributes)
- html 5: semantic tags → header, nav, main, section, article, aside, footer

### Text
- heading, paragraph, hr, br, b, i, small, strong

### Link/Media
- link → a, href, target_blank
- image → img, src, alt
- audio → audio, src, controls
- video →  video, src, controls, width
- youtube video → iframe

### List
- list → ul, ol, li, nested list (list inside a list)

### Table
- table, tr, th, td, thead, tbody, css:
    - table → border-collapse: collapse;
    - td, tr → border, padding

### Form
- form, input, placeholder, input type, css on input[type="text"] → width: 100%
    - textarea, name, id, cols, rows, select, option, value, label, legend, fieldset

### Menu using List
- menu → header > nav > ul > li > a + href + (nested list: ul > li > a, ul > li > a), css:
    - nav>ul → display: flex
    - nav li → list-style: none, margin, padding
    - nav li:hover → background-color
    - nav li .dropdown → display: none, position: absolute, background-color, padding
    - nav li"hover .dropdown → display: block