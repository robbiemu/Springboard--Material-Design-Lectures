# Material Design for Springboard Android App Development path
## lecture notes for [Google I/O 2014 - Material design: Visual style and imagery](https://www.youtube.com/watch?v=ctzWKRlTYHQ)

### Design choices

Visual design is more than a tacked-on skin. In material design there are:

* invisible grids
* roles behind the scenes
* lighting and shadow systems

#### Typography and type design

* Roboto - full family
has been reworked to fit various form factors, and to conform to be modernist/minimal. reworked numbers and italic.

this is to fulfill the purpose of providing bold, graphical typography

block out text and consider design without type so you have another sense of the presentation

Try to use larger text sizes and only shrining it based on the content.

Typographic scale is used to reduce the distinct sizes on any one screen. There should be ~3 sizes to a screen.

Type serves content, it should be quickly yielding and unobtrusive.

### Imagery

* personal
* informative
* delightful

Image doesn't have to be primary or dominant. Use textual contrast and size to emphasize text next to images.

Imagery doesn't have to be literal, just related or contextually accurate, (especially when it is beautiful/"delightful")

#### tips:
* have a focus and build a narrative (motivate user stories/use cases through the software)
- aspirational, emotional
* imagery should not hide UI, and should be scaled mindful to the app's heirarchy of importance.
- even though material design emphasizes large containers for images, the images should not overpower the use
* bold colors (imparts an intelligence to context that is well founded in a proper palette).
- intelligent color sampling automatically changes the material design palette (eventually??)

#### Avatars and thumbnails

should be actionable to a detail view. should provide access to detail that otherwise would clutter the presentation.

the user should first look to the visual, but the image should unleash the viewer to the content.

#### Gallery images

most bold, these are images unobstructed by anything but sharing the stage with other images. must be used in a well defined context.

### Color

encourage the use of bold colors.

#### Primary Color
use brand colors t base your palette. it should be the PrimaryColor

Not all screens ar the same: and density of color should match density of content. Dense screens with bold vibrant colors, and sparser screens with more pastels and variety from the palette are possible.

#### Blacks

a range of blacks for text and bold, unemphasized materials.

#### Accent color

Mean to really pop, complementary to the primary color. should probably be brighter, compared to the primary.

### Layout

* baseline grids ("layout gutters")
* keylines ("columns")
* ratios, spacing & increments ("font size in a column")

##### Keylines
60dp/80dp minimum size materials

##### increments
16dp is normal.

##### baseline grid
4dp (earlier it was 8dp)

#### Designing a layout

* when designing a layout start with blocks not text
* start with a large block size like 72dp even for text. if you shrink it, you have a dense presentation (soething to go on)
* align to the baseline

### Surface and dimension

the use of zdepth can inform the user.

tangible qualities and shadows inform the user about the materials. working from real materials provide a natural order to the design.

rendered shadows (based on z-depth in dp) render a 45º soft light source to look reasonably real, creating both a directional and halo shadow.

depth reflects separation between surfaces. (there is a default hieght for modals , fabs, etc). for this reason, subtle z-height differences may not suitable highlight content by itself. considerother alterations/transitions as well.

a lack of shadows can muddy the intent of the use case for the software.

#### shadows in use
a fab is a great example. being a poppy/accent color, and high z-depth draws attention.

#### seperation should reflect information to the user

seperating materials without purpose confuses the use story of the software, and dilutes the density of presentation.

### addendum
_see also_

google.com/design