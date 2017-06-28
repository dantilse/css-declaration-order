# CSS Declaration Order
Related property declarations should be grouped together following the order:

* Positioning
* Box model
* Typographic
* Visual

Positioning comes first because it can remove an element from the normal flow of the document and override box model related styles. The box model comes next as it dictates a component's dimensions and placement.

Everything else takes place inside the component or without impacting the previous two sections, and thus they come last.
## Positioning
### position

*   position
*   top
*   right
*   bottom
*   left
*   z-index

## Box Model
### display/visibility

*   display
*   visibility

### flex

*   flex-direction
*   flex-order
*   flex-pack
*   flex-align

### columns

*   columns
*   column-span
*   column-width
*   column-count
*   column-fill
*   column-gap
*   column-rule
*   column-rule-width
*   column-rule-style
*   column-rule-color

### float

*   float
*   clear
*   overflow
*   overflow-x
*   overflow-y
*   clip

### box-sizing

*   box-sizing

### width, height

*   min-width
*   min-height
*   max-width
*   max-height
*   width
*   height

### margin

*   margin
*   margin-top
*   margin-right
*   margin-bottom
*   margin-left

### padding

*   padding
*   padding-top
*   padding-right
*   padding-bottom
*   padding-left

### outline

*   outline
*   outline-width
*   outline-style
*   outline-color
*   outline-offset

### border

*   border
*   border-spacing
*   border-collapse
*   border-width
*   border-style
*   border-color
*   border-top
*   border-top-width
*   border-top-style
*   border-top-color
*   border-right
*   border-right-width
*   border-right-style
*   border-right-color
*   border-bottom
*   border-bottom-width
*   border-bottom-style
*   border-bottom-color
*   border-left
*   border-left-width
*   border-left-style
*   border-left-color

### border-radius

*   border-radius
*   border-top-left-radius
*   border-top-right-radius
*   border-bottom-right-radius
*   border-bottom-left-radius

### border-image

*   border-image
*   border-image-source
*   border-image-slice
*   border-image-width
*   border-image-outset
*   border-image-repeat
*   border-top-image
*   border-right-image
*   border-bottom-image
*   border-left-image
*   border-corner-image
*   border-top-left-image
*   border-top-right-image
*   border-bottom-right-image
*   border-bottom-left-image

### background

*   background
*   background-color
*   background-image
*   background-attachment
*   background-position
*   background-position-x
*   background-position-y
*   background-clip
*   background-origin
*   background-size
*   background-repeat

### box-shadow

*   box-decoration-break
*   box-shadow

### table

*   table-layout
*   caption-side
*   empty-cells

### color

*   color
*   opacity

### list

*   list-style
*   list-style-position
*   list-style-type
*   list-style-image

### text

*   quotes
*   content
*   counter-increment
*   counter-reset
*   vertical-align
*   text-align
*   text-align-last
*   text-decoration
*   text-emphasis
*   text-emphasis-position
*   text-emphasis-style
*   text-emphasis-color
*   text-indent
*   text-justify
*   text-outline
*   text-transform
*   text-wrap
*   text-overflow
*   text-overflow-ellipsis
*   text-overflow-mode
*   text-shadow
*   white-space
*   word-spacing
*   word-wrap
*   word-break
*   tab-size
*   hyphens
*   letter-spacing

### font

*   font
*   font-weight
*   font-style
*   font-variant
*   font-size-adjust
*   font-stretch
*   font-size
*   font-family
*   src
*   line-height

### filters

*   filter
*   resize
*   cursor

### nav

*   nav-index
*   nav-up
*   nav-right
*   nav-down
*   nav-left

### transition

*   transition
*   transition-delay
*   transition-timing-function
*   transition-duration
*   transition-property

### transform

*   transform
*   transform-origin

### animation

*   animation
*   animation-name
*   animation-duration
*   animation-play-state

*   animation-timing-function
*   animation-delay
*   animation-iteration-count
*   animation-direction

### direction

*   pointer-events
*   unicode-bidi
*   direction

### orphans and widows

*   break-before
*   break-inside
*   break-after
*   page-break-before
*   page-break-inside
*   page-break-after
*   orphans
*   widows

### zoom

*   zoom
*   max-zoom
*   min-zoom
*   user-zoom
*   orientation
