


 - Personally, I will keep up with the changes in web development by following a couple of blogs and people on a social media site or two like twitter. A simple search result of "Web development blogs 2020" shows many lists of blogs to follow, and the same can be said for twitter. One of the blogs I have begun to look at recently, for instance, is CSS-tricks.

 - It is very difficult to design a complex website only using floats, because floats were not designed to create layouts. The main problem is that using floats takes elements out of normal flow, which creates a lot of problems that require "hacks" to fix. Another problem is that it is hard to make adjacent elements take up the same width or height regardless of what the remaining width or height to fill content is. Finally, It is also very difficult to align things vertically with floats - an example of this is if I wanted to align some content in the middle of a container; there is really no easy way to go about it. I can use margins and such, but it can involve some tricky math that can mess up a website unintentionally.

 - One of the flex properties that affects one of the axes is the justify-content property (which affects the main axis). This property is inserted inside a flex container, and can take values of flex-start, flex-end, center, space-between, space-around, and finally space-evenly. The purpose of the property is to create spacing between the elements in the flex container in different ways. For instance, center pushes all the elements in the flex container to the very middle of the flex container, with space on either side. The result of using this property, for instance with the center value, changes when the flex-direction changes. If the flex-direction is in row, all the items in the flex container with center themselves horizontally, but if the flex-direction is column, then the items will center themselves vertically.
 The result also changes in the writing mode - if I have 4 divs inside the flexbox container, am using a flex-direction of row, have a writing mode of left to right, and I use justify-content: center;, the 1st div will be on the far left in the center, and the 4th div will be on the far right in the center. If I change the writing mode from right to left however, the 1st div will be on the far right, and the 4th div will be on the far left: their positions flip flop.