SUMMARY
-------

1. if we want to set font-size in em unit,it will consider his parent fontsize as 1em, according to that it will calculate the font size.

2. But, if we want to set padding,width etc in em unit, it will consider his own font-size as 1em, and calculate according to that.

3. There is another unit called rem, it will consider html/root as 1rem, according to that it will calculate.


IMPORTANT POINTS
----------------

i> em unit in css works relative to parent's property or own property

Ex- If parent's font size is 32px and child's font size is 2em then it is equal to 2*32px = 64px

ii> for font-size it is inherited from parent : 

        1 em = 1 * parent's font-size

    for padding, margin, border : 1 em = 1 * own font-size

iii> Advantage of padding in em: 
    
    If font-size increases padding also increases accordingly avoiding overflow

    size of padding increases with size of content

    