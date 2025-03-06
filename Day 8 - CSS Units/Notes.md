SUMMARY
-------

note: Pecentage unit is a related property.

In width & Height calculation percentage is related to parent width & Height.

In padding & Margin calculation Percentage is related to parent Width.
In font-size calculation percentage is related to parent font-size.

1. Always try to give width value in percentage unit , not in px for better practice.

2. if you want to give height value in percentage unit, user should must give their parent height value in px unit, otherwise it won't work.

3. if we want to give padding in percentage, it will calculate it from parent's width.

4. example-: parent width: 500px; we give 10% padding in his child. so our padding should be 50. 

5. Margin also work same as padding.

6. the percentage unit not work in border.

7. font-size also calaculate from it's parent font-size.

8. vh stands for viewport height and vw for viewport width. As you can see, the first unit is based on the viewport height, and 1vh is equivalent to 1% of the viewport height. vw works the same, but for viewport width. So, 1vw equals 1% of the viewport width.

CSS UNITS
---------

i> Absolute units: px

ii> Relative unit: 

    --> % (Does not work for border)

    --> vw & vh (Changes relative to viewport)


IMPORTANT POINTS AND SUMMARY
----------------------------

i> NEVER GIVE WIDTH IN PIXELS TO AVOID OVERFLOW AND UNRESPONSIVENESS. NEVER SET HEIGHT GENERALLY

ii> max-width never allow width to be more than the specified value 

iii> Width in % is calculated wrt its parent

iv> Height in % does not work if none of its parent have any height value in pixels

** RECAP: If we use box-sizing: border-box; --> padding border etc dont take extra space but takes from available width height

v> If padding and margin is in % then it is calculated wrt its parent and deviate from box model rules which is not recommended to use

vi> Font size if in % calculated acc to parent's font size. 

NOTE: Default font-size for most of the tags like <div>, <section> etc is 16px or 1em


DIFFERENT PROPERTIES AND THEIR UNITS
------------------------------------

* width --> use % || avoid px

* padding, margin --> use px || avoid %

* border --> use px || % does not work
