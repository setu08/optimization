Website Optimization
===============================

## Measures taken to improve page speed score

1. Moved required CSS for first render into a style tag on the HTML page
2. Optimized images using ImageMagick
3. Added "async" attribute on the JavaScript script tags, to load data asynchronously
4. Google PageSpeed Insights scores is above 90 on both desktop and mobile

## Measures Taken to Improve Frames per Second

1. Moved entire style.css file into HTML page for first render
2. Minified all CSS and JavaScript files
3. Optimized images using ImageMagick
4. Moved sizeSwitcher() function outside of the function
5. The frame rate came to be consistently above 60fps when measured using Chrome DevTools

## Instruction to test page speed score

1.Open Google Page Insight URL: https://developers.google.com/speed/pagespeed/insights/ and copy url http://setu08.github.io/optimization/
and paste in there.
2. For the Frames Per Second reading, open URL http://setu08.github.io/optimization/ . Open DevTools. Click on the Timeline tab. Record a     trace.

## Reference

1. ImageMagick https://www.imagemagick.org/script/index.php
2. CSS Minifier http://csscompressor.com
3. JS minifier http://jscompress.com
