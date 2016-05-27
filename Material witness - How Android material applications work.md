# Material Design
## lecture notes for [Material witness: How Android material applications work](https://www.youtube.com/watch?v=97SWYiRtF0Y)

### highlight custom work

* ripple on touch (automatic, but can be modified (slower/faster, color [default to foreground], set x/y emination point, etc)
* animations:
    explode out animations (on click to zooom/enlarge)
    click fab to unveil from fab animation
* shadows by elevation (these can also be altered programmatically instad of simply setting elevation)
    you could get a "perspective" animation by using scalex and scaley in a custom elevation (translationZ override on the View I think)
    
_note: shadows are Android L and up_

simple key concepts:
* cardViews

### sample ray tracing example

_showcasing graphics gains in mobile in receent years. he uses extreme, impressive shortcuts around raytracing._

### XML

you can use xml `objectAnimator` elemtents within ui elements to create general animations

#### activity tansitions

_animations between activities._ animation in and out for activities in stack.

info passed: position of elements, size, and bitmap, indexed by "name" (probably tag, this is passed between two activities). 

* `setExitTransition()` will let you set it up. (presumably also `setEnterTransition()`
* there are getters too, so you can add listners and override `onBackPressed` to change outcome (not full animation)
* `onAnimationUpdate` in `AnimationUpdateListener` can let you do in-animation changes more smoothly

make new activity window transparent at first (an option to show the transition exti animation).

capture inbound element tags so the new activty can animate thm inbound as visibility returns.

### Colors

color palettes in theme
`palette` utility. (it can generate a palette automatically from an image - it generates a 6-color theme though so it is different a bit)

"we want you to now use a small number of colors and some values, then tint the values with the theme colors."

Primary, PrimaryDark, Background, Accent, ControllHighlight are the 5 main colors to set up.

#### ripple animation

these can be specified in `ripple` elements in xml!

there is a Reveal method to show full on views underneith. this can allow one view to expose on press from another, and allows interactive revealed views spread from a ripple. this can be done programmatically working with the coordinates of the button.

