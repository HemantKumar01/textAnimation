# textAnimation
Uses Intersection observer to show cool animation when the element is scrolled on screen


## Usage
### 1. Text Wipe in Parts
1. save and load textAnimation.css (in head) and textAnimation.js (at end of body) in your html file
2. add class `text-wipe-in-parts` to parent element inside which words(to be animated) are present. It finds the words using regex so it does not matter whether parent element contains child elements or not.
### 2. Fade On Scroll
1. save and load animateOnScroll.css (in head) and animateOnScroll.js (at end of body) in your html file
2. add class `fade-on-scroll` to element which needs to be animated.
3. add `data-fromdirection` attribute of the same element with value one of `"bottom"`, `"top"`, `"left"`,`"right"` 