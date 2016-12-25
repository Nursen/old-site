

I'm looking for the appropriate javascript frameworks to use to create animations for the website. I don't need any of the MVC or form stuff, since everything is still static in essence, but I'd like to play around with how everything is displayed on the page. If the site ever gets bigger, it may make sense to add some dynamic loading to pull in, say, the latest 10 recipes to display on a page rather than all 50. However, I since I'm mainly using jekyll to generate the pages, if I need to move to a private server rather than gitHub and integrate whatever dynamic loading/ database sadness is required at the time. (or more likely I'll have separation anxiety and try to figure out how to make custom builds for certain pages using jekyll) In fact I can probably get away with a lot of shenanigans until performance becomes an issue. :P 

Anyways, I digress. I'm investigating the wacky world of javascript. 

This article has been useful: 

https://www.sitepoint.com/top-javascript-frameworks-libraries-tools-use/

And of the frameworks listed the ones that seem most relevant are: 

1. D3.js (https://d3js.org/) This has an impressive array of visualizations in the gallery. 
2. Three.js (threejs.org)for 3D visualizations that are simple
> Written with [StackEdit](https://stackedit.io/).

Looking closer though, I started to look for only animation frameworks and found more suitable options:
 
 This list is great: 
https://www.sitepoint.com/top-9-animation-libraries-use-2016/


1. Animate.css (https://daneden.github.io/animate.css/) Has all the animations I never knew I needed outside of MS Powerpoint. 
2. Sequence.js (http://www.sequencejs.com/) Intuitive usage, with some free "themes" but requires licensing?
3. Bounce.js (http://bouncejs.com/) Has fun bounce animations. 

And after reading even more, I'm looking most closely at these:

1.eg.js (https://naver.github.io/egjs/) A set of UI interactions, effects and utilities components library
2. bootswatch (http://bootswatch.com/) Some css files to run with.
3.  Bourbon (http://bourbon.io/) sass based (fancy inheritable css based) UI components, particularly (http://refills.bourbon.io/) which has all the UI things of eg.js but built on sass and stuff.

I'm not quite sure how sass works with other css libraries yet, so I'm going to try and figure that out. 

Cheers,
Nursen