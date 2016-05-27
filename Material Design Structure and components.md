# Material Design
## lecture notes for [Material design: Structure and components](https://www.youtube.com/watch?v=dZqzz5lZFvo)

* Material design is a guideline derrived from print, adapated to digital, animated amterial
* it is adapative to different devices, ratios, etc (responsive, in web design lingo)

Three topics:
1. Material - properties of materials themselves, 
2. Structure - both of components and interactions, and of the entire app
3. Components - practical rendition guidelines

### Materials

#### Paper and ink

Paper and ink can represent a surface (like a Canvas with a View). Paper can have a z-depth, creating dimentionality and interaction. Shadow is used to indicate seperability. Seams without shadow show related and mechanically connected material.

Rather than thinking of depth as ornament, depth can indicate importance and availability.

#### Grid: Fundamental structure of how we design our apps.

Using standard keylines, etc, we divide our material. At its source it is a grid layout. The Mat. Des. grid is an 8dp grid system.

#### How do the properties of the paper and ink affect the layout of the app?

Paper can determine the space, ink can be done in a second path. Using real paper is a plausable entry point in designing an app with material design. The structural possibilities are the same.

There are no specific required views in an app, the approach is meant to be open to its use.

Depth affects the presentation, blocking or highlighting parts of the app based on z-height. This is an example of how structure affects design.

#### App structure

App components are flexible but there are common patterns. App bars, headers, nav bars, tiles, lists, these things fulfill the app.

In specific target displays (like a mobile), the layout can respond to the way people will use the information. The density of information on the screen is important in informing the design of the app.

Primary content can be highlighted by its z-depth, as can tools and informative views.

Animation relative to function can also inform the user: parralax scrolling of images can return focus to other content and increase a sense of movement for the user.

### Components

Organization of apps should support use cases for the app. 

#### Containers 
When should cards be used instead of grids/lists?

Cards are great when you have less consistently structured data, and can make a compelling use case from their added complexity/capability.

Cards are harder to scan through, but better for browsing through.

#### Buttons, switches, other ui materials that are controls

Using simple geometric shapes. They are based on physical paper cutouts to ensure their functions maintain a relationship with the physicality of material.

There are 3 styles of buttons:

* FAB - floating action - raised. designed as a circle, highlighting key functions or materials on the app. only one per screen. not every screen should use a fab.
these can be extended to morph into a bottom bar with mutliple actions, or to spring out children ith different related subactions. these should be used more sparinly.
* raised - standard button.
* flat - inset into the background, is just ink.

### Applying material design in real apps
You can continue to use the standard library. Instead, question design already in place. Conform design aptterns to material guidelines. 

Re-plan element transitions to allow motion to provide meaning, conforming to the principles of material design. Use transitions to guide the user.

Ensure that structure relfects purpose. The user should be able to look at the design and understand the user case it was deisgned for... it should be directed.

There is a claim that materials deisgn should simplify the code base, making it easier to maintain a consistent style.