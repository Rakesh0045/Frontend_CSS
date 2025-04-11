* z-index only works if element has a specified position property

* If an element has position: relative then it is stacked above its other corresponding elements

* If multiple elements have "position: relative" then cascading rule is followed. The one at last with the property is stacked over every element

* Higher the z-index value it is stacked above others, Lesser z-index means it is stacked below others


STACKING CONTEXT IN Z-INDEX
---------------------------

Two divs have some elements stacked over each other, all elements including div container have specified position property

To manipulate the stacking order we need to take care of the container's z-index also. 

If container z-index is lower than corresponding container's then no matter how big z-index value gets, specified element will always be stacked below other container's elements