# Thank you for your interest!!
Now here's how to build my site!
(for Windows)
1) Move the styles.less file from /LESS to /node_modules/.bin
2) Switch directories so that your command line prompt is in /node_modules/.bin
3) Compile the LESS file into CSS by typing: lessc  styles.less styles.css
4) That should have generated a styles.css file, move that to /build/css (if there's already a previous file there, delete it)
Now you've prepared the styling! Then you have to generate the HTML pages
5) Switch directories so that your command line prompt is in the main project folder
6) type: node blog_generator.js
Tada, you've built the site! Now just click on an HTML page to view it in your browser!
