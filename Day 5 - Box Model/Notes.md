Summary:

0. Height & width dependent on each other.

1. To avoid overflow you should always set max-width not absolute width.

2. To avoid overflow you should always set min-height not absolute height.

3. We can also set the value in %, it always calculate & set according to it's parent.

4. in height case : if user set height in the parent wo bhi absolute value px ke sath, then it will work for child with percentage.
