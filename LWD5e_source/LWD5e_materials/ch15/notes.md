So, we have been formatting text as they appear. We will be breaknig this flow by:
- floating
- positioning

# default layout model
as it appears in the source

# breaking the default
floating - wrapping around the following text {moves it far left or right}
positioning - grid system to specify position

each block starts on a newline

# floating images
inline content reflows to fit the width of the block

<q>floating element is like an island in a stream</q>

floats stay in content area of the containing element


## floating inline elements
always provide width of content area - inline text - otherwise occupies full content width

floated line elements behave as blocks as seen from disabling width

## floating block elements
must provide width like before

## clearing float
* {clear:left/right/both}

## img[src*="muffin"]
the nifty attribute selector

