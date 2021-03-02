# Class 14 Read A

## CSS3 Animation and Transition

* Transition can change the appearance of an element if a change happened on its state, this change can be targeted using pseudo-selector like `:hoover`.

* Transition had four properties including  `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

* Not all property can be transitioned it must had a clear mid point like `color` and `z-index` properties and more.

* you can set multiple values for  `transition-duration` property if you have targeted multiple  property by `transition-property`.

* The `transition-timing-function` property is used to set the speed in which a transition will move.

```CSS3
.box {
  background: #2db34a;
  border-radius: 6px
  transition-property: background, border-radius;
  transition-duration: .2s, 1s;
  transition-timing-function: linear, ease-in;
  transition-delay: 0s, 1s;
}
.box:hover {
  background: #ff7b29;
  border-radius: 50%;
}
```

* Animation used to have more control over transition when transition need to be on multiple states.

* `@keyframes` used to declare the animation name set the animation that we want to use.

* `animation-name` property used  to set the element with a certain animation.

* `Animation-Duration`,`Animation-Timing-Function` & `Animation-Delay` is properties affect the animation like their `transition-x` sibling.

* `animation-iteration-count` used to repeat the animation when its element state kept changed.

* `animation-direction` used with `animation-iteration-count` to specify  the titrations animation direction.

* `animation-play-state` used to play or pause animations. 

*** 

* `transform:rotate();` The rotate value provides the ability to rotate an element from 0 to 360 degrees
  * positive angel it will rotate clock-wise ,counterclockwise if negative.

* `transform:scale()` : change the appearing size for an element. 

* `transform:translate*()` used to push element from its place. 

* `transform:skew*()` used to distort elements on the horizontal axis, vertical axis, or both.

* 3D transform is done by adding a z-axis parameter to the 2D's x and y axises parameters.
