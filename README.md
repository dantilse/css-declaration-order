# CSS Declaration Order
Related property declarations should be grouped together following the order:

* Positioning
* Box model
* Typographic
* Visual

Positioning comes first because it can remove an element from the normal flow of the document and override box model related styles. The box model comes next as it dictates a component's dimensions and placement.

Everything else takes place inside the component or without impacting the previous two sections, and thus they come last.
## Positioning
*   position
*   top
*   right
*   bottom
*   left
*   order (flex property)
*   z-index

## Box Model
### display
*   content
*   display
### flex
*   flex (grow | shrink | basis)
*   flex-grow
*   flex-shrink
*   flex-basis
*   flex-direction
*   flex-flow
*   flex-wrap
*   justify-content
*   align-items
*   align-content
*   align-self
### float
*   float
### width, height
*   width
*   min-width
*   max-width
*   height
*   min-height
*   max-height
### padding
*   padding (top | right | bottom | left)
*   padding-top
*   padding-right
*   padding-bottom
*   padding-left
### margin
*   margin (top | right | bottom | left)
*   margin-top
*   margin-right
*   margin-bottom
*   margin-left
### columns
*   columns (width | count)
*   column-width
*   column-count
*   column-gap
*   column-fill
*   column-rule (width | style | color)
*   column-rule-width
*   column-rule-style
*   column-rule-color
*   column-span
### orphans and widows
*   break-before
*   break-inside
*   break-after
*   page-break-before
*   page-break-inside
*   page-break-after
*   orphans
*   widows
### visibility
*   overflow
*   overflow-x
*   overflow-y
*   clear
*   clip

## Typographic
### font
*   font (style | variant | weight | size / line-height | family)
*   font-style
*   font-variant
*   font-weight
*   font-size
*   font-family
*   line-height
*   font-size-adjust
*   font-stretch
*   src
*   letter-spacing
*   hyphens
*   white-space
*   word-spacing
*   word-wrap
*   word-break
### color
*   color
### text
*   text-align
*   text-align-last
*   text-decoration (line | color)
*   text-decoration-line
*   text-decoration-color
*   text-underline-position
*   text-emphasis (style | color)
*   text-emphasis-style
*   text-emphasis-color
*   text-emphasis-position
*   text-indent
*   text-justify
*   text-outline
*   text-overflow (mode | ellipsis)
*   text-overflow-mode
*   text-overflow-ellipsis
*   text-shadow
*   text-transform
*   text-wrap
*   tab-size
*   quotes
*   vertical-align
### list
*   list-style (type | position | image)
*   list-style-type
*   list-style-position
*   list-style-image
*   counter-increment
*   counter-reset
### direction
*   pointer-events
*   cursor

## Visual
### background
*   background (color | image | position / size | repeat | origin | clip | attachment)
*   background-color
*   background-image
*   background-position
*   background-position-x
*   background-position-y
*   background-size
*   background-repeat
*   background-origin
*   background-clip
*   background-attachment
### border
*   border (width | style | color)
*   border-width
*   border-style
*   border-color
*   border-spacing
*   border-collapse
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
### border-image
*   border-image (source | slice | width | outset | repeat)
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
### border-radius
*   border-radius (top-left | top-right | bottom-right | bottom-left)
*   border-top-left-radius
*   border-top-right-radius
*   border-bottom-right-radius
*   border-bottom-left-radius
### box-shadow
*   box-decoration-break
*   box-shadow
### box-sizing
*   box-sizing
### appearance
*   outline (color | style | width)
*   outline-color
*   outline-style
*   outline-width
*   outline-offset
*   opacity
*   filter
*   visibility
*   size
*   zoom
### table
*   table-layout
*   caption-side
*   empty-cells
### transform
*   transform
*   transform-style
*   transform-origin
### animation
*   animation (name | duration | timing-function | delay | iteration-count | direction | fill-mode | play-state)
*   animation-name
*   animation-duration
*   animation-timing-function
*   animation-delay
*   animation-iteration-count
*   animation-direction
*   animation-fill-mode
*   animation-play-state
### transition
*   transition (property | duration | timing-function | delay)
*   transition-property
*   transition-duration
*   transition-timing-function
*   transition-delay
### filters
*   resize
*   unicode-bidi
*   direction
### nav
*   nav-index
*   nav-up
*   nav-right
*   nav-down
*   nav-left
