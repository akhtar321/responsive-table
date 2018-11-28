# responsive-table
Responsive Table formate 

Responsive design is all about adjusting designs to accommodate screens of different sizes. So what happens when a screen is narrower than the minimum width of a data table? You can zoom out and see the whole table, but the text size will be too small to read. Or you can zoom into the point of readability, but browsing the table will require both vertical and (sad face) horizontal scrolling.

So here's what we are gonna do...
We're going to use "responsive design" principles (CSS @media queries) to detect if the screen is smaller than the maximum squishitude of our table. If it is, we're going to reformat the table.

We're being good little developers and using Plain Ol' Semantic Markup here for our table. Bare bones example:
