<h1> Disaster Monitoring Dashboard </h1>
<h2> Description </h2>
<p> Natural disasters are a fairly common phenomena occurring multiple times in various places. Many countries maintain a database of the occurring disasters, their severity, spatial and temporal extent. For a more comprehensive evaluation and view of the occurring disasters and to facilitate timely response, a disaster monitoring dashboard is proposed. This is suggested for the United States of America, as they currently implement a similar dashboard executed using ESRI products and built using python, they also have a well maintained dataset for the disasters that occur in the country.</p>

<h2> Data Source </h2> 
<p> The dataset that would be integrated in the development of the proposed web application would be retrieved from the Open Federal Emergency Management Agency (OpenFEMA). OpenFEMA is open government data designed to foster collaborations and citizen science contributions to disaster management across the United States of America. Disaster Information over the country is provided via the data portal. With a set of GI tools, the data will be transformed into a workable format for the OpenLayers library (GeoJSON) and further integrated into a multi-layered web map application based on cartographic principles. </p> 

<h2> Functionality </h2> 

<p> The proposed web application will implement the following functionalities:<p> 
➢	Visualization of the basemap (OSM) and vector layer in the form of polygons (US states) showing the distribution of different types of disasters on state level in the US.
  <br/> 
➢	Attribute query like a state name search or an address search.
  <br/> 
➢	Spatial query which can be implemented in the form of an information pop-up when clicking on a certain state.
  <br/> 
➢	Downloadable data service.
  <br/> 
➢	Integration of statistical diagrams, indicating the characteristics of distribution of disasters.
  <br/> 
➢	Spatial-temporal visualisation realized through a time-slider. (taken as a non-goal for now)
  <br/> 
