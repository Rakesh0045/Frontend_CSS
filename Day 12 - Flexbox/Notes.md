FLEXBOX NOTES:

1) General Flex Property
------------------------

* display: flex --> makes the element for which property is applied along with its direct child as block level. ADVANTAGE --> We can give height and width to block elements

* The parent for which display:flex is given is --> "Flex Container" & all it's immediate child are --> "Flex items". Flexbox parent ki margin aur padding ko maintain krke utna space leave krke start hoti hai.

* If flexbox doesn't have available width then it shrinks content-width of all the flex items proportionately by equal %

** content-width: The width of all content if fitted in 1 line **

* The content size of a flex-item is the width of all content of that item is inserted in one line

* The final size of a flex-item is width of item after it is shrinked

2) Property: flex-shrink
------------------------

* flex-shrink: 0 --> This property ensures that the flex-item for which this property is applied doesn't shrink it's width even if contents are pushed

If this property is applied then content-size = final-size

* flex-shrink: 0.5 --> Shrink the item 50% less than the rest

3) Property: flex-grow
------------------------

* flex-grow --> By default the value of this property is 0. If its value is 1 then it grows and takes up the extra available space width 

flex-grow only works only if extra space is available

4) Property: justify-content
----------------------------

* justify-content: center --> Divides the blank space equally on all sides and bring content to center

* justify-content: space-between --> Divides blank space between consecutive flex items, first and last element stick to ends of parent container

* justify-content: space-around --> same as prev + first and last element are separated from ends of parent container by space = half of space between consecutive element

* justify-content: space-evenly --> all elements are separated from parent ends or another item by equal space

If no extra space is available then these properties won't work

5) Property: align-items
------------------------

* In flexbox the flex items generally stretch and cover the whole height of parent due to default property --> "align-items: stretch" but normally the height is same as the height of content

* If we want the height to remain same as the content in flexbox then property --> "align-items: flex-start" is used

* align-items: flex-end --> Elements cover height same as their content but stick to the end of parent container

* align-items: center --> Elements cover height same as their content but stick to the center

If no extra space in parent height these properties won't work

6) property: flex-direction
----------------------------

* By default the flex-direction: row; is applied

* flex-direction: row-reverse --> Reverses all the flex items row wise horizontally

* flex-direction: column --> flex items are arranged column-wise one top of another

When flex-direction is column then the height change and shrink exactly same way as the width changed when flex-direction: row used

align-items work horizontally in this case as compared to horizontally in flex-direction: row

# Easiest way to ceneter any element
  ----------------------------------

    display: flex;
    justify-content: center
    align-items: center

NOTE:

* width: max-content --> Increases the width so as to fix all the content in 1 line. 

* width: min-content --> Shrinks the width as much as it can. width = size of longest word in paragraph
