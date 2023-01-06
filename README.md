SASS/BEM Responsive Project
SASS preprocessor used.
When writing styles, the Mobile-first approach and the min-width media function were used.
There is no unnecessary duplication of styles in media queries.
Styles needed only in a certain span are closed in media queries (min-width) and (max-width).
The layout is made with respect to three breakpoints, as per layouts (480px, 768px and 1200px).
When viewing the page on any device, the horizontal scroll bar does not appear. All content fits into the available horizontal space.
All background and content bitmaps are responsive and support screens with x1 and x2 pixel densities.
For content images, a responsive <img> element with an x ​​descriptor is used.

All content images are responsive, support webp format and x2 pixel density. At the same time, there are fallback images in an alternative jpg or png format.