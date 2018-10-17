---
layout: default
title: "OpenCV.js release"
tags: software research
comments: true
---
OpenCV.js brings years of OpenCV development in computer vision processing to the web with high efficiency. It provides a collection of carefully selected computer vision functions ranging from image processing, object detection, video analysis, features extraction, deep neural networks, etc. Thanks to JavaScript portability, for the first time, a large collection of vision functions can be used not only on web browsers but also on embedded devices (e.g. IOTs using Node.js) and Desktop application development (e.g. Electron framework). Combined with recent web additions, it helps in realizing novel web applications and experiences such as emerging virtual and augmented reality more efficiently.

In addition, we have developed expansive online resources to help developers and researchers learn more about OpenCV.js and computer vision in general that can be accessed at:

1. [OpenCV.js documentation and tutorials](https://docs.opencv.org)
2. [OpenCV.js demos](https://codepen.io/collection/nJbkNo/)

OpenCV.js can also be used in Node.js based environments. It is published on [NPM](https://www.npmjs.com/package/opencv.js).

{% if page.comments %}
<div id="disqus_thread"></div>
<script>

/**
*  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
*  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables*/
/*
var disqus_config = function () {
this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};
*/
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = 'https://sajjadt-github-io.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}