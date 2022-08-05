# A Basic Header

Use flexbox rules to create this very common webpage header style. The benefit to using flex here is that everything should be _flexible_. Check out the two screenshots below to get an idea of how it should scale with your screen. Besides flex rules, you'll also want to add some rules for margin and padding. (Hint: `ul`s have some default margin/padding that you will need to deal with.)

## Desired Outcome

narrow:
![narrow](./desired-outcome-narrow.png)

wide: 
![wide](./desired-outcome-wide.png)

### Self Check
- There is space between all items and the edge of the header (specific px amount doesn't matter here). Yes, Using padding.
- Logo is centered vertically and horizontally. Yep, now we can use align-items
to align the flex items vertically, but for horizontal alignment, justify-content even I don't think it will ALWAYS horizontally centered the logo. Margin auto
will gauranteed that.
- list-items are horizontal, and are centered vertically inside the header. 
Yes, it's set to display: flex in ul. Since their containers are child
of header class and header class is display: flex. Then it too be be 
aligned vertically.
- left-links and right-links are pushed all the way to the left and right, and stay at the edge of the header when the page is resized. Yes, padding header 
class put alittle bit of padding next to them.
- Your solution does not use floats, inline-block, or absolute positioning.
Nope, glad that there isn't one.
