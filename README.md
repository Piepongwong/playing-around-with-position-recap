# Playing around with Position Values

The 3 most important position values are:

* relative (relative to its normal position)
* absolute (relative to its parent element)
* fixed (relative to the viewport)

The position values are terribly named in my opinion, especially absolute. Absolute is relative to its parent container. Another catch is that if you want to position something with absolute, its parent container needs to have its position set as well. That can be relative without setting left, right, top or bottom. 

If the position of an element is set, its substracted from the normal document flow, because it gets another z-index.