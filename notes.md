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
- We can control the gutters further even with responsiveness at breakpoints e.g. g-sm-10

v. Utitlities

- displaying flex in bootstrap is by adding the "d-flex" to the class. Then we use the align-items-{position} and "justify-contents-{position}"
- We use the p-{number} for padding.

vi. CSS Grids

- To add a grid, <div class="grid"></div>
- To add a grid column, "g-col-{breakpoint}-{number}"

2. Contents
   i. Reboot

- To do contents in bootstrap, it is important to set a configuration where all the config styles like fonts, font family, and other important constants for the project are store.

ii. Typography

- This include all the global settings, fonts, and other typography-related groups
- To set the font of a tag to a heading, just set the class to "h{num}" e.g <span class="h2">
- Display also has 6 types in bootstrap <div class="display{number}">
- To make a paragraph stand out, add lead to it. e.g. <p class="lead">
- We can also make abbreviations, blockquotes, and list typography good

iii. Images

3. Forms

- Bootstrap for forms is a ton of styles for creating form layouts, styles, components, and form function.

i. Form control

- Since an input field depends on the data that is being collected, we use the input and label tag for text and other text related input.
- The class of the label is set to "form-label" or "col-form-label" and the for the input, "form-control" or "col-form-control"
- For color picker, the input type is set to color and class attribute to "form-control form-control-color"
- For datalist, the input field list attribute is set to the id of the datalist id and the input field still take form control.
- For a dropdown, the select container class attribute is "form-select" and the label attribute is still set to form-label.
- For checkbox, radio buttons, and switches, the bootstrap classes look familiar. Their main container is set to "form-check"; the form input is set to "form-check-input"; the form label is set to "form-check-label"; for switches, the input receives an addition attribute, called role="switch" and the class receives an additonal style "form-control" on the switch container form class. e.g <input type="checkbox" class="form-check-input" role="switch"  />

4. components
i. The acordion
- To set an accordion on a section of the page, the accordion container must be set. it's class must be set to "accordion". Then in the accordion container, you can add multiple acordion elements. 
- An accordion element has 2 parts, a header and a body. The header is a div with class "accordion-header" and the header contains of a button with the "accordion-button" class. the button takes other attributes like the type, data-bs-toggle, data-bs-control, aria-controls, aria-collapse.
- The accordion body has the class "accordion-collapse" with a data-bs-parent attribute pointing to the id of the accordion container. In the accrodion is the "accordion-body" in a div component.

ii. alerts
- They provide contextual data for user actions.
- the alert is just a div with a class of "alert alert-{type}" and role="alert"
