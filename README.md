# web-performance-bootcamp

Useful links:
* https://surma.dev/things/less-snakeoil/
* https://developers.google.com/web/fundamentals/performance/rendering/stick-to-compositor-only-properties-and-manage-layer-count
* https://csstriggers.com/
* https://github.com/devkodeio/web-performance-bootcamp

Performance BootCamp

https://github.com/devkodeio/web-performance-bootcamp

Critical rendering Path: sequence of steps to convert html, css and js to pixels on screen.
First html fetched and it is read first. For links and scripts they are fetched.
			Html => DOM
Network=>					=> RenderTree=>Layout=>paint
			CSS=> CSSOM
	
Latence 3g/4g————————|————In-App-Performance———|

Html-> bytes->Characters->Tokens

https://www.youtube.com/watch?v=K-AqHUiL-bI

Max 6 resources can be loaded parallely (browser specific) (Also per domain) Some companies use multiple domains to load lot of resources in parallel.

rel= “prelaod” “pre-fetch” “dns-prefetch”

Web pack-5 Udacity

Lazy-load-images:

Intersection Observer => Learn this! What all elements are there in viewport.

https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API

https://caniuse.com/loading-lazy-attr

DOMContentLoaded should be less.

Data-src on images for lazy loading images.

LightHouse:

Layout-thrashing:

https://csstriggers.com/

Web pack light wallet(google plugin)

SDE-2?: system-design, better quality code,  system design: design patterns FE, Design Google Calendar (plug & play pattern, pub sub pattern) what is in MVP?(1hr), 
