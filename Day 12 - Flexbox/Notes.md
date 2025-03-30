FLEXBOX SUMMARY:

* display: flex --> makes the element for which property is applied along with its direct child as block level. ADVANTAGE --> We can give height and width to block elements

* The parent for which display:flex is given is --> "Flex Container" & all it's immediate child are --> "Flex items". Flexbox parent ki margin aur padding ko maintain krke utna space leave krke start hoti hai.

* If flexbox doesn't have available width then it shrinks content-width of all the flex items proportionately by equal %

** content-width: The width of all content if fitted in 1 line **

* The content size of a flex-item is the width of all content of that item is inserted in one line

* The final size of a flex-item is width of item after it is shrinked

* flex-shrink: 0 --> This property ensures that the flex-item for which this property is applied doesn't shrink it's width even if contents are pushed

If this property is applied then content-size = final-size

NOTE:

* width: max-content --> Increases the width so as to fix all the content in 1 line

* width: min-content --> Shrinks the width as much as it can. width = size of longest word in paragraph
