### Page Load
* [Google's best practices](https://developers.google.com/speed/docs/best-practices/rules_intro), and [this ](https://developers.google.com/speed/pagespeed/)
* [Speeding up trello boards](http://blog.fogcreek.com/we-spent-a-week-making-trello-boards-load-extremely-fast-heres-how-we-did-it/)

### Assets
* [Advanced Image Optimization Tricks](http://sixrevisions.com/web-development/advanced-image-optimization/)
* [Tips For Optimising SVG Delivery For The Web](calendar.perfplanet.com/2014/tips-for-optimising-svg-delivery-for-the-web/)

### CSS
* [Style guide by a GitHub engineer](https://speakerdeck.com/bleikamp/sass-at-github)
* [CSS Documentation framework](https://github.com/kneath/kss)


### Links
* [Yahoo! Best Practices for Speeding Up Your Web Site](http://developer.yahoo.com/performance/rules.html)
* [Safari Image Delivery Best Practices](https://developer.apple.com/library/safari/documentation/NetworkingInternet/Conceptual/SafariImageDeliveryBestPractices/Introduction/Introduction.html)
* [Safari: Serving Images Efficiently to Displays of Varying Pixel Density](https://developer.apple.com/library/safari/documentation/NetworkingInternet/Conceptual/SafariImageDeliveryBestPractices/ServingImagestoRetinaDisplays/ServingImagestoRetinaDisplays.html)
* [Breaking 1000ms Time to Glass loading barrier](http://www.youtube.com/watch?v=Il4swGfTOSM)


***



* **Compressive Images** Daan Jobsis, a dutch designer, found a very strange phenomenon when compressing images with Photoshop. He proved the following: Take an image, double its size (200%), compress it to 25% or less its original quality, resize it back in the browser(100%). The image will not only be lighter in size but already optimized for HiDPI screens, since its pixel density is already doubled.
The only observed problem is that the browser might have a hard time painting a double-sized image back to its original size (if it has to do it a hundred times, like in image-heavy sites). A little bit of testing is required to see if this is the optimal solution.

* **Asset Loading:** Load assets carefully and in order. Controlling this aspect provides a big advantage, by allowing the page to render the basic content and enhance it afterwards.


* **CSS, Images**: Controlled loading through media queries, conditional or lazy loading and responsive / compressive image techniques

* **JavaScript:** Make use of HTML5 functionality, likeasync or defer. There are also loading helpers like RequireJS that can handle loading and dependencies.
