## Website Performance Optimization Project

The project is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make the page render as quickly as possible by applying the techniques learned at [Critical Rendering Path course](https://www.udacity.com/course/ud884).

##What I did 

At first run, the site scored 29/100 on desktop and 26/100 for mobile on Google Pagespeed Insights.

1. Optimize Images: resize and compress. Score increased to 68 mobile -- 81 desktop
2. JS: Load JS asyncronously, move scripts out of head to the bottom of body
3. CSS: Add media="print" for styles that are used to print. Removed Google fonts, since it wasn't worth an extra render-blocking resource. Score: 82 -- 88 
4.Minify and compress CSS and JS. score: 94-95. 
5. Only thing left is server side: leverage browser caching, but this is a local site only site. 

The biggest gains were from optimizing images and then from removing render-blocking css for above-the fold content.
