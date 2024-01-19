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

