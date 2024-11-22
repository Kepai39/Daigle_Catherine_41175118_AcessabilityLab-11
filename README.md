# Accessibility Lab 11 Questions and Answers:

## What is the keyboard interaction missing? :
The focus indicator was not visible when tabbing, the CSS file had set the focus outline: none.  That should be removed

## What is the ARIA missing?
ARIA is missing Aria expand = true/false, to let users know that the Accordian collapsed or expanded.  It is also missing aria-labelledby referencing the button ID as well as aria-controls = "id".  the div is also missing an aria-hidden = "true" or else the screen reader keeps reading the content as its collapsed.

