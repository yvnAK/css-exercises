# Mistakes
Only made the '.header' a flex display.  <br>
This makes all of the blocks of stuff in the header apply to what you've styled it as. <br>
Your issue of the links not being in rows is because _the 'ul' needs to be flex as well._ <br>
Left links and right links don't need to be touched, and instead in '.header', padding needs to be 8px, the justification should be 'space-between', and there should be no changes to the 'flex-flow'.  <br>
'ul' should have 0 margin and padding, and a gap of 8px. <br>

The padding in the header adds space between the links and the top/bottom of the header. <br>
Items are aligned in the centre, meaning they are floating in the middle, and justification is 'space-between' meaning the items have some spacing between them.  <br>
Not sure what the ul padding and margin do, but the gap is what pushes links apart. More gap means more space between one two and three.