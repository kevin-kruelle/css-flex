# CSS Flexbox Layout


## Part 1

* Start with the larger screen and work your way to smaller. Begin with a fresh layout and do not use media queries. 
* Place your `nav` AFTER the `main` content.
* Create a `<div class="container">` that encompasses the `<body>`.  
* Set the `header` and `footer` to fill the width of the screen using `flex: flex-grow flex-shrink flex-basis;` (with values included). 
* Using `order: x`, display elements visually by ordering `header` first, then `nav`, `main`, `sidebar`, and finally `footer`.



## Part 2

* Make `nav` and `aside` the same size using the same `flex-grow` and `flex-shrink` values. 
* The `main` content should be larger than `nav` and `aside` in normal width (not mobile).
* When `.container` is larger than 900px, distribute items evenly. When `.container` is smaller than 900px, items that don't fit should wrap to the next line.  
* Use a `flex-shrink` to ensure items are not removed from `nav` and `aside` items. 
* Use `body` as a flex container. The `<div class="container">` becomes the child. Set a  `display-flex` to `body` content to `justify-content: center` to center the content of the page on large widths, but still fill the width on smaller screens.