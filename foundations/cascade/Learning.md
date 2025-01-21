# Cascade
## Smaller paragraph with bold text
Put 'small-para' after 'para'. This works due to rule order as both selectors have the same specificity.
Otherwise, increase specificity by renaming 'small-para' to 'p.small-para' to increase specificity.

Whichever item comes later takes precedence, or the more specific style takes precedence.

## Confirm Button
Put '.confirm' under the '.button' rule.

This makes the confirm button take greater precedence than the regular button rule.

## Smaller Child Div
Put '.child' after 'div.text' and then change '.child' into 'div .child'.
Otherwise, keep it where it is, and change it to '.text .child'