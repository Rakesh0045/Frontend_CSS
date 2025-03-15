IMPORTANT POINTS
----------------

i> The transform CSS property lets you rotate, scale, skew, or translate an element.

** In transform-origin property we have to mention the cordinates from where our element starts growing

Ex- If we mention 0 0 then it grows from top left corner and grows towards the right side

If we mention 100% 100% then it grows from bottom right corner to other sides (left side)

ii> alpha chaining in rgba property reduces the intensity of the
color. An alpha channel is a grayscale channel that indicates how transparent a pixel is. It's used to create images with transparent or semi-transparent areas. 

iii> opacity of an element refers to the transparency level

opacity vs alpha channel
------------------------

alpha channel can only make the background transparent

opacity can make the whole element including the content transparent

HOW TO CENTER A DIV
-------------------

    position: absolute;
    left: 50%;
    top: 50%;
    /* Element is moved 50% left and top from the element to which it is attatched */
    transform: translate(-50%,-50%);

    When we use transform translate -50% -50% then the element moves dist = half of its width in -ve x direction and dist = half of its height in -ve y direction

iv> Box shadow property: <h-offset v-offset blur spread color>   

#h-offset:	Required. The horizontal offset of the shadow. A positive value puts the shadow on the right side of the box, a negative value puts the shadow on the left side of the box	

#v-offset: Vertical offset of the shadow, A positive value puts the shadow on the bottom of the box

#spread: The spread radius. A positive value increases the size of the shadow

v> Never use background property to change bg color, use background-color property always to change bg color

    background-size: contain;
    /* Used to cover the whole image inside the box */
    background-repeat: cover;
    /* Repeat the image to cover the box */
    background-position: -30px -15px;
    /* Change position of the image in x and y direction */

vi> transition property is used to give animation effect to all the transitioning elements who shifts position (ex-translate)

transition is used to add time delay to the transitioning element to make it smooth
