<!DOCTYPE html>
<html>

<head>
	<meta charset=utf-8 />
	<title>Map Template Browser Title</title>
	<meta name='viewport' content='initial-scale=1,maximum-scale=1,user-scalable=no' />

	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/5.0.0/normalize.css" />
	<link rel="stylesheet" href="https://unpkg.com/leaflet@1.0.1/dist/leaflet.css" />
	<link href="https://fonts.googleapis.com/css?family=Noto+Sans" rel="stylesheet">
	<link href="https://fonts.googleapis.com/css?family=Lora" rel="stylesheet">

	<style>
		body {
			margin: 0;
			padding: 0;
			background: "whitesmoke";
			font-family: "Noto Sans", sans-serif;
			color: #3d3d3d;
		}

		h1 {
			position: absolute;
			margin-top: 0;
			top: 10px;
			left: 45px;
			font-size: 2em;
			font-family: "Lora", serif;
			letter-spacing: .04em;
			padding: 10px 15px;
			background: rgba(256, 256, 256);
			border: 1px solid grey;
			border-radius: 3px;
			z-index: 800;
		}

		h2 {
			font-family: "Lora", serif;
			letter-spacing: .04em;
		}

		#map {
			position: absolute;
			top: 0;
			bottom: 0;
			width: 100%;
		}

		section {
			position: absolute;
			bottom: 0;
			left: 10px;
			width: 280px;
			margin: 20px auto;
			padding: 0 15px;
			background: rgba(256, 256, 256);
			border: 1px solid grey;
			border-radius: 3px;
			z-index: 800;
		}

		p {
			font-size: .9em;
			line-height: 1.5em;
		}

		a {
			color: #005daa;
			text-decoration: none;
		}

		a:hover {
			text-decoration: underline;
		}
	</style>
</head>

<body>

	<h1>Patsy Pond </h1>

	<div id='map'></div>

	<section>
		<h2>About this map</h2>

		<p> Patsy Pond is located in the Croatan National Forest in Carteret County, NC. This is one of the more scenic parts of the Mountain to Sea trail, a 1,175 mile trail from the mountains of North Carolina to the coast.  
		<p> One common draw to Patsy Pond is the ease and smoothness of the trails. Located in the pine-filled Savannah plains of the coast, many rare and exotic plants can be found. Commonly found just off of the trails are <i>Dionaea muscipula</i>, or more commonly known as the Venus Flytrap, only found in a small span of the eastern coast of North Carolina. Many other common carnivorous plants found are <i>Sarracenia spp.,<i> "Pitcher Plants", and </i> Drosera spp.,</i> "Sundews".
			<p>More information on Patsy Pond can be found <a href="https://www.fs.usda.gov/recarea/nfsnc/recarea/?recid=48502">here</a></p>

		<p>Map authored by , Cameron Oaks</p>

	</section>

	<script src="http://code.jquery.com/jquery-3.1.1.min.js"></script>
	<script src="https://unpkg.com/leaflet@1.0.1/dist/leaflet.js"></script>

	<script src="data/Route.js"></script>

	<script>

//options to be used when creating the map
		var options = {
			center: [36.08402, -81.3015],
			zoom: 15
		}

		console.log(data);

//creation of the Leaflet map
		var map = L.map('map', options);

//request to load basemap
var Esri_WorldTopoMap = L.tileLayer('https://server.arcgisonline.com/ArcGIS/rest/services/World_Topo_Map/MapServer/tile/{z}/{y}/{x}', {
	attribution: 'Tiles &copy; Esri &mdash; Esri, DeLorme, NAVTEQ, TomTom, Intermap, iPC, USGS, FAO, NPS, NRCAN, GeoBase, Kadaster NL, Ordnance Survey, Esri Japan, METI, Esri China (Hong Kong), and the GIS User Community'
}).addTo(map);

//string content to be inserted into a tooltip
		var message = 'Patsy Pond!';

//create a Leaflet marker, centered on the map's center.
		L.marker(map.getCenter())
			.bindTooltip(message) //bind the tooltip and message to the marker

			.addTo(map) // add the marker to the map`
			.openTooltip(); // open the tooltip

var myRoute = L.geoJson(data, {
 filter : function(feature) {
 if(feature.geometry.type =="LineString") {
 return feature;
 }
},
 style : function(feature) {
 return {
 color: "#FF8000",
 weight: 6,
 opacity: 1.0,
 dashArray: "7, 7"
 }
 }
 }).addTo(map);
 var myStops = L.geoJson(data, {
 filter : function(feature) {
 if(feature.geometry.type == "Point") {
 return feature;
 }
 },
 onEachFeature : function(feature, layer) {
layer.bindTooltip(feature.properties['name']);
 }
 }).addTo(map);

map.fitBounds(myRoute.getBounds());


	</script>

</body>

</html>
