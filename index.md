# Explore a Human Hair Fiber <!-- Loads <model-viewer> for old browsers like IE11: -->
<h2 style="text-align: center;" markdown="1"> Discover a 2nd Augmented Reality Experience!</h2> 
<script nomodule="" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js">
  </script>

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


<h2 style="text-align: center;" markdown="1">BREADCRUMB #1</h2> 
<h2 style="text-align: center;" markdown="1"><a href="https://www.AVERtek.net" onclick="getOutboundLink('https://www.AVERtek.net'); return false;"> BREADCRUMB #2</a></h2>
<h2 style="text-align: center;" markdown="1">BREADCRUMB #3 <a href="https://avertek.net/special-bonus" onclick="getOutboundLink("https://avertek.net/special-bonus"); return false;">[REWARD HERE]</a></h2>
## BREADCRUMB #3 **[REWARD HERE]("https://avertek.net/special-bonus")**

---

<h3 style="text-align: center;" markdown="1"><a href="https://avertek.net/" onclick="getOutboundLink('https://avertek.net/'); return false;">Learn More About AVERtek's XR-NOW</a></h3> 
  
