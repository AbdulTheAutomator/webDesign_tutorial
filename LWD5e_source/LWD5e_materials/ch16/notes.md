# flexbox
all of the child elements become part of flex container

e.g. nav ul {
display:flex;
}

this will make all _list items_ part of flex container as li is child of nav ul

> all children line up with one axis. for bidirectional adjustments we use __grid__ instead (not flexbox!)


if flexbox container: you can use order on img selector to make it appear on top

when flex property is set, everything gets evenly spaced - no need to define height and width for contents

# grid
you can't imagine spans and cells in the head - best to sketch it out first

fr unit: flex factor - good for responsive design

grid-template-columns: 200px repeat(5,20px 1fr) 200px;

let browser figure out space itself
grid-template-rows: repeat(auto-fill, 10em)

