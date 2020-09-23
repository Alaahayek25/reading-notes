## CSS Transforms
The transform property allows authors to resize, position and change elements; this can be on either the two-dimensional (2D) or three-dimensional (3D) setting. Before getting into the their individual properties and values it is good to know that the general syntax for the transform property is very simple; include the transform property followed by the value and its specific values inside parentheses.

- 2D Scale: using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.
- 2D Translate: using the translateX value will change the position of an element on the horizontal axis while using the translateY value will change the position of an element on the vertical axis.
- 2D Skew: the last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or both.


##  CSS Transitions
With CSS3 transitions you have the potential to alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, focused on, active, or targeted.
Transitional Property:

 the transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties.
Transitional Properties: 

it is important to note, not all properties may be transitioned, only properties that have an identifiable halfway point. Colors, font sizes, and the alike may be transitioned from one value to another as they have recognizable values in-between one another.


Transition Duration: the duration in which a transition takes place is set using the transition-duration property. The value of this property can be set using general timing values, including seconds (s) and milliseconds (ms).
Transition Timing:

 the transition-timing-function property is used to set the speed in which a transition will move.
Transition Delay:

 determines how long a transition should be stalled before executing.


## Animations
When multiple transitions are required, the transition property becomes obsolete and the animation property becomes the focus. To set multiple points at which an element should transition, we use the @keyframes rule, which includes the animation name, any animation breakpoints, and the properties intended to be animated.

