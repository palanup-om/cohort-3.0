# css (cascarding style sheet)

#  what a way to write css 
- inline css
- extrenal css
- internal css


# css selector

- element selector 
- class selector
- id selector
- attribute selector


# css selector 
- descent selector
- children selector
- Descendant selector
- child selector
- adjacent sibling
- general sibling
- group selector
- universal selector


# Pseudo-classes — styles based on state
- /* Link states */
- a:link    { color: blue; }      /* Unvisited */
- a:visited { color: purple; }    /* Visited */
- a:hover   { color: red; }       /* Hovered */
- a:active  { color: orange; }    /* Being clicked */
- a:focus   { outline: 2px solid blue; } /* Keyboard focused */

# Form states 
- input:focus   { border-color: blue; }
- input:disabled { opacity: 0.5; }
- input:checked  { accent-color: green; }
- input:required { border-color: red; }
- input:valid    { border-color: green; }
- input:invalid  { border-color: red; }
- input:placeholder-shown { border-style: dashed; }

/* Structural pseudo-classes */
- li:first-child    { font-weight: bold; }
- li:last-child     { border-bottom: none; }
- li:nth-child(2)   { color: red; }       /* exactly the 2nd child */
- li:nth-child(odd) { background: #f5f5f5; } /* odd rows */
- li:nth-child(even){ background: white; }   /* even rows */
- li:nth-child(3n)  { color: blue; }      /* every 3rd: 3, 6, 9... */
- p:only-child      { margin: 0; }        /* only child of its parent */
- p:not(.special)   { color: gray; }      /* everything except .special */

/* Others */
- .card:hover > .overlay { opacity: 1; }
