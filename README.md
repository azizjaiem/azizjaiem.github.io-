<!DOCTYPE html>
<html>
  <head>
    <title>Simple Map</title>
    <script src="https://polyfill.io/v3/polyfill.min.js?features=default"></script>
    <link rel="stylesheet" type="text/css" href="./style.css" />
    <script src="./index.js"></script>
  </head>
  <body>
    <div id="map"></div>

    <!-- Async script executes immediately and must be after any DOM elements used in callback. -->
    <script 

    src="https://maps.googleapis.com/maps/api/js?key=AIzaSyC8iFTcus8zJKcEK9vX42VuhtMmukWSnEs&callback=initMap&libraries=places&v=weekly"
      async
    ></script>
    
  </body>
</html>
