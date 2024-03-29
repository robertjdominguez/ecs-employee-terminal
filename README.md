﻿# ecs-employee-terminal
## Directions
In this second project, we'll learn some new skills! Notably, we'll talk about utilizing **images** as the background of an element. We'll also create **buttons** from anchor tags for the first time and use a different way of selecting/applying CSS rules with **hover**.

### Image as background
This is a pretty easy thing to accomplish, so long as we have **good** quality art! Below, we're going to give the path to the image file as the value of the background property:
```CSS
.image-card {
  background: url('../images/rolling_hills.jpg');
}
```

### Hover selector
CSS allows us to modify the appearance of elements depending on certain events. One of these events is when a user hovers over an element. This is a useful tool to help the user understand that an element _does_ something and keeps them oriented on the page. For example, when a user hovers over a button:
```CSS
/* This is how the element will appear when NOT being hovered over */
.button:hover {
  background: red;
  color: white;
}

/* our clas is called 'button' but the colon and 'hover' afterwards mean that these rules are only applied to it ON a hover event */
.button:hover {
  background: darkred;
  color: grey;
}
```
