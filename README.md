# Project 3: CSS Grid

A responsive car collection page converted from the Project 2 Flexbox layout to CSS Grid.

**GitHub Pages:** https://toumas12.github.io/comp584-project3/

The page uses one column on mobile, two on tablet, and four on desktop. Cards span multiple columns where needed, and the final row uses five equal columns on desktop.

The additional `grid-auto-rows: minmax(12rem, auto)` property sets a 12rem minimum for implicit rows while allowing rows to grow when their content needs more space. The `repeat()` and `minmax()` functions size the grid tracks responsively.

Open `index.html` in a browser to view the page locally.
