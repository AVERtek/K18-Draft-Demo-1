# Explore a Human Hair Fiber <!-- Loads <model-viewer> for old browsers like IE11: -->
<h2 style="text-align: center;" markdown="1"> Discover a 2nd Augmented Reality Experience!</h2> 
<script nomodule="" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js">
  </script>

  <!-- The following libraries and polyfills are recommended to maximize browser support -->  
  <!-- REQUIRED: Web Components polyfill to support Edge and Firefox < 63 -->
  <script src="https://unpkg.com/@webcomponents/webcomponentsjs/webcomponents-loader.js"></script>

  <!-- OPTIONAL: Intersection Observer polyfill for better performance in Safari and IE11 -->
  <script src="https://unpkg.com/intersection-observer/intersection-observer.js"></script>

  <!-- OPTIONAL: Resize Observer polyfill improves resize behavior in non-Chrome browsers -->
  <script src="https://unpkg.com/resize-observer-polyfill/dist/ResizeObserver.js"></script>

  <!-- OPTIONAL: Fullscreen polyfill is required for experimental AR features in Canary -->
  <!--<script src="https://unpkg.com/fullscreen-polyfill/dist/fullscreen.polyfill.js"></script>-->

  <!-- OPTIONAL: Include prismatic.js for Magic Leap support -->
  <!--<script src="https://unpkg.com/@magicleap/prismatic/prismatic.min.js"></script>-->
  
  

  
   

<script>
/**
* Function that registers a click on an outbound link in Analytics.
* This function takes a valid URL string as an argument, and uses that URL string
* as the event label. Setting the transport method to 'beacon' lets the hit be sent
* using 'navigator.sendBeacon' in browser that support it.
*/
var getOutboundLink = function(url) {
  gtag('event', 'click', {
    'event_category': 'outbound',
    'event_label': url,
    'transport_type': 'beacon',
    'event_callback': function(){document.location = url;}
  });
}
</script>

<!-- Loads <model-viewer> for modern browsers: -->
 <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.js">
  </script>
<script nomodule="" src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js"></script>
<script src="{{ "/assets/js/scale.fix.js" | relative_url }}"></script>

<!-- Loads <model-viewer> for modern browsers: -->
 <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.js">
  </script>
<script nomodule="" src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js"></script>
<h2 style="text-align: center;" markdown="1">BREADCRUMB #1</h2> 
<h2 style="text-align: center;" markdown="1"><a href="https://www.AVERtek.net" onclick="getOutboundLink('https://www.AVERtek.net'); return false;"> BREADCRUMB #2</a></h2>
## BREADCRUMB #3 **[REWARD HERE](https://avertek.net/special-bonus)**

---

<h3 style="text-align: center;" markdown="1"><a href="https://avertek.net/" onclick="getOutboundLink('https://avertek.net/'); return false;">Learn More About AVERtek's XR-NOW</a></h3> 
  
