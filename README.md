<!DOCTYPE html>
<html>

<head>
    <meta name="viewport" content="width=device-width"> <link href="css/index.css" rel="stylesheet" type="text/css">
    <script type="text/javascript" src="cordova.js"></script>
    <script type="text/javascript" src="js/starbucks_hawaii_stores.json"></script>
    <script type="text/javascript" src="js/index.js"></script>
</head>

<body>
    
    <div id="map_canvas">
        <span id="label" style="background-color:white;padding:.5em;font-size:125%;position:fixed;right:0;top:0;"></span>
        <button id="removeClusterBtn" style="position:fixed;bottom:0;right:0;padding:.5em;font-size:125%;">markerCluster.remove()</button>
    </div>

</body>

</html>
