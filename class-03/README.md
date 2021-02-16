## Flexbox and Templating

### Templating with Mustache

* **Mustache** is a logic-less template specification.\
* **Mustache.js** is an implementation of **Mustache** in javaScript.

***

### A Guide to Flexbox

**Container properties**

* `display:flex;` is a property that you give to the container by which it gives *inline* or *block* display values to items inside the container.

* `flex-direction` the direction in which the children elements will line up.

* `flex-wrap ` usually the items will try to line up on the same row for *row* direction, using this property will force any excess items to go down to the next row.

* `flex-flow` is a shorthand version for `flex-direction` and `flex-wrap`.

* `justify-content` this property controls the alignment of the items inside the container.

* `align-items` is for vertical alignment 


**Items properties**

* `flex-grow` defines the ability of the items to grow if there is an empty space in the container.

* `flex-shrink` defines the ability of the items to shrink if necessary.

* `flex-basis` controls the size of the item before the remaining space is distributed, using `auto` will use the default width and height of the element.

* `flex` is a shorthand version of `flex-grow`, `flex-shrink` and `flex-basis`