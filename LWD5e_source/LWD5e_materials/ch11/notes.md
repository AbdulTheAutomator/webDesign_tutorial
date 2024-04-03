# inheritance
e.g. <em> tag inherits from sans serif css font-family </em>

- properties relating to styling are inherited
- properties relating to boxed area are not


# dom

html has implicit hiearchy


html = head{title,style,meta} : body{content:semantic}

ancestor (anything higher than parent) => parent => child's

# conflicting styles
- user agent style sheet/ user style sheet (browser default)
- !important overrides are priorities (useful when you know there will be conflict down the line)

> p{color: blue !important;} where !important is to the declaration

- specificity wins in selector styling e.g. #id > p selector

- last rule always wins

- <style>@import url(some_external_sheet.css); rest_of_selectors;</style>

# box model
every element is contained within a little box whether its inline or block level

# grouped selectors
separate selectors by comma

# css units
- q is 1/4 of a mm
- px = 1/96 of inch

relative units based on default property
- em = current font size
- rem = root element (html) size
- good for responsive design
- vw/vh  = 1/100 of viewport width and height respectively
- vmin/vmax = viewport max unit equal to vw or vh whatever is larger
- child inherits calculated font size not the actual rel value e.g. actualy px of parents not the em value

__relative units are way to go due to viewports of devices__

em of one element may not be the same of the other




 
