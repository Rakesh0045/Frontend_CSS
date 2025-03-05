Summary :- 

1. We use padding because to generate space around an element's content  

2. Border by default color set as our text color, but we can overright it.

3. when we add padding & border the overral width of the box will increse , to avoid that we can use one property (box-sizing: border-box;) . 

4. Margin will not affect our inner content. it apply in the outside of the box.

5. for making circle using border radius property, user should must apply width & height.

6. the outline is drawn outside the element's border, and may overlap other content. Also, the outline is NOT a part of the element's dimensions; the element's total width and height is not affected by the width of the outline



1. In inline element, width & height doesn't workout. width & height dependend on inner content.  

2. if we add padding & border in inline element it's overral height & width increses.

3. when padding & border applied to an inline element the top and bottom padding's affect the surrounding elements.

4. in inline elements, everything works inline, for top & buttom it doesn't work properly.

5. To avoid these type of problem, user should use display: inline-block. 

6. There are two types of inline element, one is replaced another is non replaced.

for replaced elements every property works properly even if the element is inline example -: <iframe>,<video>,<embed>,<img> 

non-replaced elements are as similar as inline elements. examples -: span, strong, i, b, em