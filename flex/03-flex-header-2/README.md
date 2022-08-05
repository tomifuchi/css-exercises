# Another common header style

We're starting to sneak in a little more CSS that you haven't seen yet. Don't worry about this for now; we just want things to look a little bit prettier, and this CSS will not interfere with your task.

For this one you will probably need to edit the HTML a little bit. Often with flexbox you need to add containers around things to make them go where you need them to go. In this case, you probably want to separate the items that go on the left and right of the header.

This is also the first example where you'll be nesting flex containers inside each other.

## Desired outcome
As with the last example, this one needs to be flexible in the middle, with items pushed to the left and right.

![png](./desired-outcome.png)

![gif](./desired-outcome.gif)

### Self Check
- Everything is centered vertically inside the header. With align-items
I can be sure it's centered vertically.
- There is 8px space between everything and the edge of the header.
padding .8% to be exact, looks better that way.
- Items are arranged horizontally as seen in the outcome image. Yes
Split into 2 divs, left and right, inside nested 1 flex container for the
links.
- There is 16px between each item on both sides of the header.
Approximately gap of 10px. But close enough.
- flex is used to arrange everything. Of course, everything. Not one
single floats, inline-block or anything else, works perfectly.
