# Material Design for Springboard Android App Development path
## lecture notes for [Google I/O 2014 -Material science: Developing Android applications with material design](https://www.youtube.com/watch?v=lSH9aKXjgt8)

### Why?

#### Motion

there's a heavy bloat-worrysome standard here, what justifies it?

**Motion matters.**
it can inform the user.

* Motion + Tangibility = more intuitive UX for users

**Translation of design to solution (engineerng)**

Engineers need to be able to implement artistic ideas in a standardized way.

There ar tools for this in material design:

* shadows
* activity transitions
* reveal
* recyclerView
* touch feedback (z-height)
* performance optimizations for all of this

### How?

* design
* use 'widgets': paradigms of material design (ard view, recycler view, etc)
* use material apis - ripple, shadows,clipping, icons with state changes (transitions, reveals)
* appCompat pbackports much o this a good ways

#### UI Toolkit features

_these are new in L_

##### Widgets (Available appompat)

* recyclerview - has tieins to animate, adaptar standardization, custom layout
* cardview - an item view with specific presentatin goals.

##### Graphics

* z-height shadows are calculated (faked pre-L)

the performance is optimized

you have access to the internals such as:
* setElevation
* setTraslationZ
* setZ

**touch feedback** interaction is available as well (as we went over in a previous lecture)

* rippledrawable class wraps drawable and reveals it over time. it has a color value as well
* Custom iews can use rippledrawable as well

**icons**

statelistanimator
specify animations between states
xml specified animation (flip-board style animation)

**animations**

animation curves
can be set/manipulated
there are 3 default timing curves

pathinterpolator define control and anchor points

objectanimator can animate with paths.

**transitions**
window transitions
activity transitions
animate when launching (changing activities)
    animate on exit
    animate on entrance
    "share elements"
shared elements are transfered via activityoptions

done with

setEntertransition
setExitTransition

share element with:
activityopions.makeSceneTransitionAnimation 

tranisition customizations are available as well (move/slide, etc)