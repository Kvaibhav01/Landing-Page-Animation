## Landing Page Animation

Create smooth and beautiful landing page animation using only basic CSS animations.

[![forthebadge](https://forthebadge.com/images/badges/validated-html5.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/uses-css.svg)](https://forthebadge.com)

## Example
![](animation.gif)
### LIVE DEMO: https://kvaibhav01.github.io/Landing-Page-Animation/

## How-to?

If you know basic CSS along with its animations you can quickly add this type of _landing page_ animation in your [SVG](https://www.w3schools.com/html/html5_svg.asp) files as shown in the demo. I recommend you to take the [W3School's tutorial](https://www.w3schools.com/css/css3_animations.asp) on the same. 

In your CSS file, you need to have the following:

- **[`animation`](https://www.w3schools.com/cssref/css3_pr_animation.asp)**: assign a keyframe animation name as `monitorIn`, duration of `1s`, animation type of `ease-in-out` and animation direction as `forwards`. 
- **[`@keyframes`](https://www.w3schools.com/cssref/css3_pr_animation-keyframes.asp) `monitorIn`**: next, use the `keyframe` rule of `from` `to` in order to [`transform`](https://www.w3schools.com/cssref/css3_pr_transform.asp) and define [`translation`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/translate) along Y-axis only setting the `opacity` accordingly.
- **`@keyframes chatblips`**: for the `chatblips` keyframe, I've used the `bounce-in` [animation sample](http://angrytools.com/css/animation/) taken from [Angry Tools](http://angrytools.com) website. This uses the CSS [`scale()`](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/scale) function to resize the element on 2D plane.

#### That's it! Simple, clean and smooth! 

Read [this article](https://codeburst.io/create-a-beautiful-landing-page-animation-with-css-8f4501c20c8e) I wrote to incorporate it in your project.
