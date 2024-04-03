# color and backgrounds
# difference between psuedo class and elements
special state of an element
style specific parts of an element

## pseudo class selectors

keeping tracks of states e.g. visited link colour change

indicated by : e.g. a:link | a:visited

helps control element's state css or link states

## action pseudo-classes (:)
### pattern
<element>:pseudo-class

:focus selected and ready for input
:hover pointer over element
:active process of being clicked or tapped (instantaneous!)

input:focus{background-color:yellow}
> use :focus style for keyboard tabbing

#### other classes

> structural pseudo-classes & input pseudo-classes & location & linguistic & logical

## pseudo elements (::)
inserts fictional elements into the document
### ::before ::after
generate content before and after pseudo-elements

## guidance on pseudo-element
best to keep it unlinked to content as it doesn't reside in DOM

## attribute selectors
> class and id selectors are special type of attribute selectors

helps us avoid use of class and id markup

much borrowed from regex

element[attribute]
element[attribute=exact_val]
element[attribut~=val] //kind of like a wild card search for value *find_me*
element[attribute|=val] //hypen separated attribute val selector
element[attribute^=first part of the value] //beginning substring
element[attribute$=last part of the value] //last part of substring
element[attribute\*="any part of the value"]

## background
element {background: background-color,background-image,background-repeat,background-position,background-attachment}

## modular approach
using @import

