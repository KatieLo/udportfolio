## Website Performance Optimization portfolio project

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

#What I did 

At first run, the site scored 29/100 on desktop and 26/100 for mobile.

## Desktop

1. Optimize Images: resize and compress. Score increased t0 68 -- 81
2. JS: Load JS asyncronously, move scripts out of head to the bottom of body
3. CSS: Add media="print" for styles that are used to print. Removed Google fonts, since it wasn;t worth an extra render-blocking resource. Score: 82 -- 88 
4.Minify and compress CSS and JS. score: 94-95. 
5. Only thing left is server side: leverage browser caching, but this is a local site only site. 
