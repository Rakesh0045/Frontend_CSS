MEDIA TYPE
----------

* media types are used to manipulate our content based on some media queries like print, screen, all etc

* There are 3 @media type:-

i> @media print --> means the changes/manipulations will be visible when we print the contents not when we are seeing it on web screen

ii> @media all --> means the changes/manipulations will be visible everywhere while seeing the content on web screen as well as when we print the contents 

iii> @media screen --> means the changes/manipulations will be visible only while seeing the content on web screen but not visible when we print the contents 


MEDIA FEATURES
--------------

i> @media (orientation: portrait): It will be applied when the orientation of our content will be in portrait

ii> @media (width <=> 700px): When width is above 500px the changes will be applied otherwise not

iii> @media (max-width:700px): when max-width is 700px (700 or below) the changes will be applied. If width crosses 700px then changes are not applied

iv> @media (min-width:700px): changes applied only when width is at least 700 or higher


MEDIA QUERIES
-------------

MEDIA QUERIES = MEDIA TYPE + MEDIA FEATURES

* @media print and (min-width: 500px) --> changes will be applied when the content is printed and the width is 500px or more