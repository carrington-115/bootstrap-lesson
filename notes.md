Bootstrap Lessons

1. Layout

i. Breakpoint
- .container: takes sets the max-width of the container to 100%
- .container-{breakpoint}: sets the width of the container to 100% till it reaches the breakpoint
- .container-fluid: sets the width to that of the whole viewport.

ii. Grids
- Bootstrap adopts a flexbox grid system that uses 12-grid system to position elements on the viewport
- The grid system can control the size and behaviour of each breakpoints with the right property
- For example to control the size of a column, # col-4
- The command (col-4) spans the width of the column to 4 out of 12 column spaces
- Through adjustings the column classes, we can specify what happens to the breakpoints on each device
For example: <div class="col-sm-6"> ---> This means on a large device, the column will take 6 columns out of 12.
- col-auto specifies the column width to the natural size of the box
- The <div class="row row-cols-{col_number}"> is a faster way to develop the grid system for a website
- For inner nesting, the data just have to follow the -row, -col structure

iii. Columns
- In the bootstrap flex-box grid system, we can align, order, and offset column components
- We can align vertically the row or the individual columns in the row by add the align-items-{position}. The position can be start, center, and end.
- We can also align individual columns by align-self-{position}. Same, the position can be start, center, and end.
- We can justify content horizontally but by using the justify-content-{position} for the entire row and justify-self-{position} for the individual column
- To send a part of the row to the next line, just add an element and specify the width to 100% (w-100%)
- We can order through adding the order-{number} class. The number must not be sequential. The order is performed by checking the value of the number

iv. Controlling Gutter
- We can control vertically or horizontally between the page elements
- We can control horizontal gutters by passing gx-{number}; vertical by gy-{number}
- We can control both the horizontal and vertical gutters by g-{number}
- 

