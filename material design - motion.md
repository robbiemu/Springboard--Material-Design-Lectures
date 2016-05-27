# Material design : Motion for Springboard Android App development path
## lecture notes from [Google I/O 2014 - Material design: Motion](https://www.youtube.com/watch?v=FBD0VlcVS1E)

### What use does motion have in motion?

it should not be superficial, but improve UX.

* every app, feature, action, tell a user story and that explains what has happened and motives the continuation (and provides a chance to abort it)
motion should be simple, and informative
* material and motion should respond to the user. motion particularly should reinforce responsiveness to the user. ripple touch animations inform the user of a recieved touch event, for example.

### Elements of traditional animation in material design motion

1. familiarity - physical world-reflective materials and motions should help contectualize the user.
- avoid extreme motions like camera zooms that can jar against he container of the physical device
2. using a degree of motionblur like effects to suggest materials motion
3. using elasticity to inform the user of maximals and range in the animation of an interface element
- you can customize the curves in the ramp of speed of the animations in generic animations
- arcs are more natural than lines, so transitions feel less mechanical when done along an arc.
- thoughtful timing of actions to guide the user in the UX.
- an ethic of craftsmanship (Attention to detail, in color, transition, and appropriate scale) fulfill the promise of motion to the user.

### Real world example:

####indicators

are a commonly animated element of your design. these can be tailored to a variety fo uses.

* spinners
* slidebars
* image loading can fade in from low contrast/sat to high

### theoretical

* timing and degree of change should agree.
*  transitions happen in ink as well as material
* using ink for modal fade of background helps focus the action, creating a story for the user through coreography and motion
* size of the device can inform the animations as well: larger screens dont go always well with large animations. tiny screens may find small transitions too irrelevant.

### wearables
(the current paradigm relies on hidden kowledge, as not every action has an onscreen control where you can use it)

in this case, animations can hint controls (like swipe left/swipe right) by quickyl showing and then hiding the options.

#### "nod" animation

non-verbal communication can be added to the design of an app through motion. A nod of an appearing indicator may acknoledge the user's previous intent, showing that the task is ready.

#### frameworks

particularly in animations, there are lots of these things built in to the system. rely on it, and build upon it, before replacing it.

make motion part of the design process from the beginning (recognize motion "moments" where a standard use makes sense, then add more to them as needed in each use case).

