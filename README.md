Data viz components:
1. Slum Population, 2014
2. Visitor data
3. Onsite study
4. Donation Simulator
example of the visual https://www.washingtonpost.com/graphics/2020/health/coronavirus-how-epidemics-spread-and-end/ ;
how to plot point cloud in d3 https://bocoup.com/blog/smoothly-animate-thousands-of-points-with-html5-canvas-and-d3 ;
Point Cloud code example: 
1) http://bl.ocks.org/dianaow/6a50292357511ceac3b78fc0fab4a2b5; 
2) https://observablehq.com/@fil/disc-transport

Use React: 
1. normally  https://www.npmjs.com/ where all js packages are hosted. But for js coding in browser content distripution network (CDN) is typically used. unpkg.com is a CDN for npmjs.com
2. search for unpkg react, or go to https://unpkg.com/browse/react@17.0.1/
3. go to umd folder / open production.js file / click view raw / copy url
4. paste in your index.html file in scr tag:   <script src=https://unpkg.com/react@17.0.1/umd/react.production.min.js></script>
5. create a budle file, that puts together all jsx elements > create new index.js file within the file tree > paste console.log(React) > bundle.js is created automatically.
6. connect index.html with bundle.js: 
7. Add ReactDOM from unpkg.
8. step-by-step is in this video: https://www.youtube.com/watch?v=2LhoCfjm8R4 at 55:00 
