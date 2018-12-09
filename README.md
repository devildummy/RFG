# RFG

Today we talk about responsive web Design and look at few questions:
  
What does responsive mean?
How should we use it?
Why should we use it?

RWD an approach in which websites creates with the instention to easy viewing with minimum resizes 
and excess scrolling for big quantity of devices

Adaptive web design is also approach, in which
provides best viewing in preset devices and resolutions

Now we can't say which approach is better
Each have own advantages and disadvantages

How we can do responsive?

Relative units
Instead of static units we can use relative,
which relate at screen size, and help us 
hold all content at users screen

Nested object
If you had a lot of relative elements, 
it would be hard to control positions of
them all. Use wrapper, to make it easer

Maximun And Minimum
Its really cool, when content take all width of your device.
But only on smartphanes. What you will see, if open site like this
an 55 inc TV?

Breackpoints
Breackpoints help change positions of
elements in case of user width. Here at 
the desktop we have two columns, and at 
mobile only one

we can use font-icons instead of picture-icons
because we can use font-size, font-color ,etc.
but we must remember about downloading

because of size changes, images can loose 
them quality, and to avoid it, better way to use 
vector images, such as svg. But you must remember,
that vector images has more weight

there is two different ways to make RWD or AWD.
Desktop-first and mobile-first.
There is no difference, how to start,
but we must understand, than user from mobile usually
has less internet connection speed, then pc-user, 
and can be underground, or in air...
Choose carefuly

Why should use?
To make a long story short - now mobile devices are even more popular
in intenet, than PC

Flexbox is a property set, which created to help
developers to position elements, and solve some old problems

Flexbox has two axes, main and cross,
also has container and elements

to use flexbox model we must set 'flex'
or 'inline-flex' property to container;
after that each child element become flex 

justify-content property alignin content
via main axis

align-items property alignin content
via cross axis

flex-direction set direction of
main axis

flex-wrap set line breacks of container

flex-flow set direction of
main axis and wrap at the same time

align-content can alignt lines
works only when flex-direction
and flex-wrap set;

order set order of viewing elements,
zero by default

flex-basis set default width of element,
which need to use flex-shrink nad flex-grow

flex-grow / flex-shrink set how elements changing 
responsive by other elementswork only with flex-basis

flex shortly set grow, shrink and basis

align-self set self elements align via 
cross axis

Grid layout is two-dimensional grid-based layout

Matn therms is a track, cell, line and area

display 
defines the element as a grid container and 
establishes a new grid formatting context for its contents.

grid-template-columns / grid-tamplate-rows
Defines the columns and rows of the grid with a space-separated 
list of values. The values represent the track size, and the 
space between them represents the grid line.
Note the bracket syntax for the line names

you can add two names to one line
and use repeat to shortcut. first argument is
count of repeated element, second is size (can be width names)

you can also use new fr size

Grid areas
Defines a grid template by names

grid-template
A shorthand for setting grid-template-rows,
grid-template-columns, and grid-template-areas
in a single declaration.

grid-column-gap / grid-row-gap
Specifies the size of the grid lines.

grid-gap
Shorhand for both

justify-items
Aligns grid items along the inline (row) axis

align-items
Aligns grid items along the block (column) axis

place-items
place-items sets both the align-items 
and justify-items properties in a single 
declaration.

justify-content
you can set the alignment of the grid within the grid container.
This property aligns the grid along the inline (row) axis

align-content
This property aligns the grid 
along the block (column) axis

place-content
define both

float, display: inline-block, 
display: table-cell, vertical-align and 
column-* properties have no effect on a grid item.

grid-column-start
grid-column-end
grid-row-start
grid-row-end
Determines a grid item's 
location within the grid

grid-column
grid-row
Shorthand for grid-column-start+ grid-column-end, 
and grid-row-start + grid-row-end

grid-area
Gives an item a name so that 
it can be referenced by a template 
created with the grid-template-areas property.

justify-self
Aligns a grid item inside a 
cell along the inline (row) axis

align-self
Aligns a grid item inside a 
cell along the block (column) axis

Float is a CSS position property

common values is right, left and inherit

If this parent element contained nothing but 
floated elements, the height of it would literally 
collapse to nothing

An element that has the 
clear property set on it will 
not move up adjacent to the float 
like the float desires, but will move 
itself down past the float

Left and right values used
to only clear the float from one direction respectively.
Both clears floats coming from either direction.
also has inherit value.

























































































