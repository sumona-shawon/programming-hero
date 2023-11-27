### Basics
- adding css, css syntax, css selectors, comment
- css specificity: !important > inline > id > class > tag > internal > external
- css measuring units → px, %, rem, vw, vh
- debug styles using devtool on browser

### Color & Font
- color, background color
- font family, font size, font weight, text align, text decoration, list-style

### Box model
- height, width, border, margin, padding, box model
- border color, border style, border radius, box shadow
- max width, margin: auto
- width: calc(100%-500px)

### Background Image
- background, background image: url(), background-image: none
- background size, background repeat, background position
- background blend mode

### Position
- position → relative, absolute, sticky, fixed + (top, bottom, left, right, z-index)

### Pseudo class & element
- pseudo class → hover, focus, visited
- pseudo element → first-child, last-child, nth-child(n), before, after

### Display
- display → inline, block, inline-block, none

### Flexbox
- display: flex, justify-content, align-items, gap, flex-direction, flex-wrap

### Grid
- display: grid
- grid-template-columns, grid-template-rows
- row-gap, column-gap 
- grid-column, grid-row

### Overflow
- overflow, overflow-x, overflow-y
- white-space: nowrap, text-overflow: ellipsis, overflow: hidden, title (tooltip on html)

### Transition & Transform
- transition: property duration timing function delay
- transform: scale() rotate() translate()
- transform-origin: top right

### Animation
- @keyframes identifier{}
    - from, to / 0%, 50%, 100%
- animation: name duration timing-function delay iteration-count direction fill-mode;
- animation-play-state: infinite

### CSS Custom Property
- :root{}
    - --primary-color: green
- background-color: var(--primary-color)

### Responsiveness using Media Query
- @media screen and (min-width: 576px) and (max-width: 992px){}
    - use bootstrap breakpoints for different devices
    - apply css as needed
    - use relative font size
    - put image inside div, width: 100% on image, resize div
    - max-width, margin: auto on body (optional)