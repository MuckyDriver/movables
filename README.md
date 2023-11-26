# Movables Documentation Document

![movables thumbnail](movables_thumb2.gif) 

## About Movables
Movables is a quick and easy CSS and JS (Jquery included) tool that allows you to apply objects to move into place when such 
element is scrolled into view. You can use Movables to make the effect of loading in different elements onto the webpage as you 
are scrolling through it. 

## Requirements
For this tool to work you will need
1. `movables.vanilla.js` **OR** `movables.jquery.js` (Jquery Edition is recommened, but both versions work exactly the same!)
2. `movables.css`
3. Put this inside the **<head>** of your HTML document **<script src="movables.vanilla.js" defer></script>** (Make sure to include "defer" as it needs to wait for all web content to be loaded in first.)

## How to setup
Here is a simple setup tutorial on how to use Movables in your site.

1. Link the Movables script and CSS to your HTML document
```html
<head>
    <!-- Movables CSS Insertion -->
    <link rel="stylesheet" type="text/css" href="https://dhcweblogistics.net/web-tools/css/movables.css">

    <!-- Movables Script Insertion -->
    <script src="https://dhcweblogistics.net/web-tools/js/movables.vanilla.js" defer></script>
</head>
```

2. Create an element that uses the **"movable"** class. (Example: opacity)
```html
<body>
    <div class="movable opacity">
        <!-- Put content here -->
    </div>
</body>
```

3. Yay! Everything should work as intended.

## Feature Documentation
Movables is not going to be as simple as you think when you do not know what kinds of effects there are and types.

**Before you start**, add `movable` to the classlist :smile:

### Movables - Types
Here is a list of different types

- Default type does not require anything - it automatically uses default timing function.
- `type-linear`: Movable will move in a linear fashion (constant).
- `type-overshoot`: Movable will overshoot for a brief moment until stopping.
- `type-back`: Movable will go backwards in the beginning and go forward until stopping.
- `type-steps-#`: Movable will move in a set amount of frames (32, 24, 12, 8, 6, 4, 2).

```html
<div class="movable opacity type-steps-12"></div>
```

### Movables - Speeds
Here is a list of different speeds that a movable can be.

- Default speed is **0.5s**
- `fast`: Movable will complete in **0.2s**
- `slow`: Movable will complete in **1s**

```html
<div class="movable opacity fast"></div>
```

### Movables - Delay
Need to add a delay to your Movable, here are the options

- Default will have no delay
- `fast-delay`: Movable will be delayed by **0.2s**
- `delay`: Movable will be delayed by **0.4s**
- `slow-delay`: Movable will be delayed by **0.8s**
  
```html
<div class="movable opacity delay"></div>
```

### Movables - Basics
Simple Movable features that require not too much knowledge.

- *One of these must be used for a movable to work!*
- `opacity`: Opacity movable will fade the object into the page.
- `blur`: Element will go back to normal from a blur effect.
- `grayscale`: Element will go from grayscale to full saturation. (Cannot use `blur` at the same time!)

```html
<div class="movable opacity"></div>
<div class="movable blur"></div>
<div class="movable grayscale"></div>
```

### Movables - From 
Movables that come in from a certain direction:

- `from-left`: Element will slide in from the left.
- `from-right`: Element will slide in from the right.
- `from-top`: Element will slide in from the top.
- `from-bottom`: Element will slide in from the bottom.

More "from" directions:

- `from-top-left`: Element will slide from the top left.
- `from-top-right`: Element will slide from the top right.
- `from-bottom-left`: Element will slide from the bottom left.
- `from-bottom-right`: Element will slide from the bottom right.

### Movables - Rotate
Rotation effects, element will rotate when in view from **-90deg**.

- `rotate`: Will rotate the element from **-90deg** to **0deg**.

Rotation can be applied to "from" directions:

- `from-left-rotate`: WIll rotate into place aswell as sliding from the left.
- `from-right-rotate`: WIll rotate into place aswell as sliding from the right.
- `from-top-rotate`: WIll rotate into place aswell as sliding from the top.
- `from-bottom-rotate`: WIll rotate into place aswell as sliding from the bottom.

More "from" directions included with "rotate" effect:

- `from-top-left-rotate`: Rotates into place as it slides from top left direction.
- `from-bottom-left-rotate`: Rotates into place as it slides from bottom left direction.
- `from-top-right-rotate`: Rotates into place as it slides from top right direction.
- `from-bottom-right-rotate`: Rotates into place as it slides from bottom right direction.

### Movables - Grow
Movable that will grow an element when in view. 

- `grow`: Will expand the element to its proper size.

Grow can also be used in "from" directions:

- `from-left-grow`: Grows and slides from the left.
- `from-right-grow`: Grows and slides from the right.
- `from-top-grow`: Grows and slides from the top.
- `from-bottom-grow`: Grows and slides from the bottom.

More "from" directions can be applied for "grow" effect:

- `from-top-left-grow`: Grows into place as it slides from top left direction.
- `from-bottom-left-grow`: Grows into place as it slides from bottom left direction.
- `from-top-right-grow`: Grows into place as it slides from top right direction.
- `from-bottom-right-grow`: Grows into place as it slides from bottom right direction.

### Movables - Shrink
Movable that will shrink an element when in view. 

- `shrink`: Will shrink the element to its proper size.

Grow can also be used in "from" directions:

- `from-left-shrink`: Shrinks and slides from the left.
- `from-right-shrink`: Shrinks and slides from the right.
- `from-top-shrink`: Shrinks and slides from the top.
- `from-bottom-shrink`: Shrinks and slides from the bottom.

More "from" directions can be applied for "shrink" effect:

- `from-top-left-shrink`: Shrinks into place as it slides from top left direction.
- `from-bottom-left-shrink`: Shrinks into place as it slides from bottom left direction.
- `from-top-right-shrink`: Shrinks into place as it slides from top right direction.
- `from-bottom-right-shrink`: Shrinks into place as it slides from bottom right direction.

***
## Thank you :D
Thanks for using this web-tool, I hope to make more and to add more features to this
one.

> :warning: If you choose to download the resources beware you may miss out of updates to the live version on `https://dhcweblogistics.net/web-tools/`. 

*Version 1.0*
