# Day 2
__12/01/2020__

## Thoughts on CSS

### What is a pseudo-class and what are some of the most common ones I will use? 
  Pseudo-classes are special predefined classes that reference a specific state of an element.  Style rules created for psuedo-classes will affect elements only when they are in that specific state. One of the seemingly more common ones is the :hover pseudo-class, which refers to an element when the mouse cursor is, as you would assume, hovering over it. Given the number of times I see this used in most websites, I imagine I will use it quite frequently in the future as well.

### What is specificity and how might I use it to my benefit?
  Specificity is a value that is assigned to a specific style rule or set of rules; it is determined by the combination of selectors used for those style rules. Using various degrees of specification when deciding on selectors and keeping specificity values in mind will allow cleaner and simpler code. General rules can then be applied once and only overridden in corner cases, versus needing to individually style each element one by one.

### What problems might arise from the overuse of the `!important` feature?
  Not entirely unrelated to the above point, overuse of !important detracts from the value of the specificity feature. It could also cause difficulties when refactoring or implementing design changes in the future. An alternative would be to add an #id to important selectors for which you want a style overridden, combined with proper utilization of ordering in the css style document. Only when these approaches fall short should the use of !important be considered.

#### Afternoon Lab: [Cool Site](https://trevor-r-allen.github.io/coolsite/)
