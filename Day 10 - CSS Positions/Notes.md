SUMMARY
-------

* By default all elements have position value as static

* Relative positioning works wrt current position of element

* position: unset --> unsets all the positioning changes

* child with position: absolute is connected/attatched to any of its parent with position property is available, else it is attatched to the viewport

* position: fixed is always attatched to viewport irrespective of parent's positioning otherwise it is same as position: absolute    

* child never goes outside the parent in the case of STICKY POSITIONING. It only moves around within the parent but when it reaches edges like top and bottom, it sticks to the parent and moves along with it

* child with position: sticky attatches itself to the parent with overflow: scroll property, else it is attatched to the viewport. 



IMPORTANT POINTS
----------------

i> By default all elements have position value as static

# POSITION : RELATIVE

ii> Relative positioning works wrt current position of element and moves related to current position

    position: relative;
    top: 50px;
    bottom: 50px; 
    
    when we use top:50px in relative positioning our element maintains a margin of 50px from top

    Same goes for bottom: 50px

    top: -50px is same as bottom: 50px --> maintain a margin of 50px from bottom or move 50px closer to top

    ----------------------

    left: 50px;

    element maintains margin of 50px from left and sometimes a scrollbar is added if the content goes beyond device width

    left: -50px;

    element moves 50px towards left, in this case no scrollbar is added even if content overflows

iii> top: 5px;
    bottom: 5px;
    left: 5px;
    right: 5px;
    
    inset: 5px;
    
    In case of conflicting positions like this, first one prevails

    Here top and left position property overrules bottom and right

    inset: 5px; does the same job in 1 line


iv> position: unset --> unsets all the previous positions and make them as default (static)

# POSITION : ABSOLUTE

v> Absolute positioning works wrt position of viewport in case parent do not have any specified position property

    top: 5px --> element moves 5px from topmost part of viewport

    left: 5px --> element moves 5px from left of viewport

** If any of the parent has predefined position property then positioning is done wrt the parent  

** If child position is absolute and any parent position is not relative then parent and child do not stay attatched together in case margin padding are applied --> If child is absolute then parent position must be relative, so that parent and child are attatched

# child with position: absolute is connected/attatched to any of its parent with position property is available, else it is attatched to the viewport

vi> top: 5px;
    bottom: 5px;
    left: 5px;
    right: 5px; 

    inset: 5px;

    Whole viewport is covered with the element with 5px gap from all sides

# POSITION : FIXED       

vii> position: fixed is always attatched to viewport irrespective of parent's positioning otherwise it is same as position: absolute    

# POSITION : STICKY

** If we use position: sticky then child does not go outside the parent. It only moves around within the parent

** It moves with the parent and remain inside it but when it reaches edges like top and bottom, it sticks to the parent and moves along with it

** It is used to make scrollable navbars

** It attatches itself to the parent who have overflow: scroll property and moves along with it