FLEXBOX NOTES
-------------

i> How to give Equal width to all flex items
   -----------------------------------------

* To give equal width to every flex item we need to give width: 100% to every item. In that way, all items initially have 100% width of viewport but then shrinked equally to accomodate multiple items

Ex- Viewport width - 900px
    Total Flex-items - 3

    All flex items initially had base size 900 px width but later they were shrinked by equal % to accomodate other items

    Final size: 300px

NOTE: If the items are shrinked excessively then they may not get equal width as min-width comes into the picture

Default min-width of item : width of longest word in the content


ii> Property: flex-basis
    --------------------

* flex-basis sets the initial size (width for flex-direction: row or height for flex-direction: column) of a flex item before any available space is distributed, allowing for flexible sizing and layout control. 

* when flex-basis is used the base-size of item is computed from this property instead of taking from width or content-size

* flex-basis defines the starting size of a flex item before flex-grow and flex-shrink come into play. 


iii> flex-basis vs width
     -------------------

* flex-basis depends on flex-direction. 

If flex-direction is row --> then it gives width to flex-item

If flex-direction is column --> then it gives height to flex-item

* flex-basis can grow to accomodate extra content 

iv> flex-wrap
    ---------

* flex-wrap: wrap; --> If width/space is not available then instead of shrinking it will send content to new line   


v> gap
   ---

* gap property maintains gaps between flex-items. Even if the items are shrinked, the gap is maintained

* "row-gap" --> maintains gap between rows
  "column-gap" --> maintains gap between column

vi> Centering Element using margin
    ------------------------------

* margin-top, margin-bottom doesn't work if display: flex is not used

* margin: auto in flexbox bringes the element to the center

NOTE:  margin-block --> shorthand for margin top and bottom
       margin-inline --> shorthand for margin left and right

These margin-block and margin-inline doesn't affect one another  

vii> order property
     --------------

* By default order property value is 0 

* More the order value of an item, the item gets displayed towards the end

* Item with least order value comes first

viii> property: align-self
      --------------------

* Used to align a single particular flex-item  

flex: flex-basis, flex-grow, flex-shrink --> shorthand to use 3 property in 1

ix> align-items: baseline vs align-items: flex-start
    ------------------------------------------------

* Both of these align items to start of the parent but if one of the item's font size is bigger then the difference is noticed   

* In baseline, if one item has bigger font size, then the other items will be aligned from the bigger font alphabets end/base line of bigger font content

x> property: align-content
   -----------------------

*  When there are multiple lines while using flex-wrap, to center those multiple lines we have to use align-content  

* align-content keeps the multiple lines aligned and together, align-items just keep the flex-items aligned

xi> display: inline-flex
    --------------------

* The elements which have this property applied behave as inline block, they act as block element, we can give height width to it unlike inline elements

* Elements with display: inline-flex doesn't take up full width and allows other items to take the remianing width/space available


       



