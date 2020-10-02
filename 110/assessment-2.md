
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

- Specificity is what determines which selector is applied when multiple selectors apply to the same element. 
For instance, in-line CSS is applied to an element over a selector in a CSS stylesheet that is selecting the same 
element. The term cascade basically means that if two selectors have the same specificity, then the selector that 
comes in last is the one that is applied.
