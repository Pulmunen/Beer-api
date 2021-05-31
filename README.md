# Beer-api

Solved a problem with some checkboxes not being accessible because css covered them with other elements.  Root cause of the problem was that a class name was used to fulfil 2 different roles on 2 different types of container.  The first use was in the initial html and css, the second was added by Javascript.

The Javascript was left untouched, changes made in html and css.
