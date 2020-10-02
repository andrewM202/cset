
- So far, I have enjoyed the filter property the most. It is used, as its name implies, to apply image filters to a given element - 
like opacity, brightness, and so on. The filter property can take the value none, or any of the filter functions, and 
the filter function can take a percent or numerical value. I like
it just because it is fun to apply various filters and see how my content might look different - it is also useful to test different 
color gradients and color schemes using filter functions like brightness, invert, and so on, without finding new hex code values
each time. 

<br>

- One option to select specific menu options that are using the same HTML elementswould be to only use class selectors. 
This way, I can simply apply the correct class (like spicy or veg for vegetarian) to the corresponding
food type for each menu option, and style each class of food separately. I can also add multiple classes to each element, in case one of the menu options
spicy and gluten-free for instance. 
<br>
An example of only using class selectors:

```
<style>
 .veg {
  ...
 }
 
 .spicy {
  ...
 }
 
 .gluten-free {
  ...
 }
</style>
<ul>
 <li class="veg">Vegan burger</li>
 <li class="spicy">Ghost peppers</li>
 <li class="gluten-free">Brown rice</li>
 ...
</ul>
```

<br>

- Specificity, cascade, and inheritance are different things but are all related to each other. Specificity is what determines which property is applied when multiple selectors are targeting the same element, 
and are both applying the same properties. For instance, a class or identity selector's properties will be 
applied over the same properties in an element selector, 
even if that element selector comes before the class or ID selector in the stylesheet. The term cascade basically means 
that if two selectors have the same specificity and properties, then the selector that comes in last is the one whose properties
is applied (as mentioned in the previous sentence).
Finally, inheritance describes when a child element also gets the properties of its parent element. These concepts are useful to know
in organizing CSS - it leads to a design of having general/broad selectors at the top of one's stylesheet, with more specific selectors at the bottom.
For instance, I may use the universal selector `*` at the top of my stylesheet in order to set all my elements with a margin and padding of zero.
Later on in my CSS, I can then have a div that has a margin of five pixels, and know that the five pixel value will be the one that is applied. 






