# SASS
  ***Sass** makes easier for us to simplify and maintain the style sheets for our projects*.
  
  ***Sass** is a CSS pre-processor*.

## Features of SASS
  - Variables
  - Nesting
  - Functions
  
     * We use the **$** sign to assign the value. 
     * SASS uses the **@if, @else if, @for, @each, and @while** CSS rule like JavaScript. [SASS Logic](https://learn.freecodecamp.org/front-end-libraries/sass/use-if-and-else-to-add-logic-to-your-styles/)
     * SASS uses the **.SCSS** file extension.
     * **Partials** are used for in Sass This is a great way to group similar code into a module to keep it organized. We use **@import** to used in our Sass files. [@import](https://learn.freecodecamp.org/front-end-libraries/sass/split-your-styles-into-smaller-chunks-with-partials/) 
     * SASS use the **Mixins** it is a block of re-usable code that can take arguments and we use **@include** to apply in our code. [@mixin](https://guide.freecodecamp.org/miscellaneous/sass-syntax-and-tools/)
     * **@extend** is the other feature of SASS, which is **borrow** the CSS rule from the other class name if we need to apply the same properties and values. [@extend](https://learn.freecodecamp.org/front-end-libraries/sass/extend-one-set-of-css-styles-to-another-element)
     
## code snippet for @extend
``` 
.panel{
    background-color: red;
    height: 70px;
    border: 2px solid green;
  }
```

```
.big-panel{
  @extend .panel;
  width: 150px;
  font-size: 2em;
}
```
