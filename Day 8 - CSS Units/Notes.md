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