Chaco_Canyon_Project (Building Phases)
This project was constructed using tile base maps from OpenTopoMap (https://opentopomap.org/#map=9/38.3524/-105.8835). This map was downloaded as part of 
XYZ Tiles using QGIS 3.38 Grenoble software. Annotation data was taken from the books, "Archaeology and Archaeologists: Chaco Canyon," by Robert H. Lister & 
Florence C. Lister, and "The Chaco Canyon Handbook: An Encyclopedic Guide," by R. Gwinn Vivian & Bruce Hilpert.  

This map was created as the base map for a multi-phase project to depict differing areas of Chaco Canyon and the location of Great Houses, water sources,
and other features not commonly found or challenging to compile from other sources.  Specifically, this map shows the location of Great Houses within Chaco Canyon 
with annotations to their initial construction year.  These construction periods are annotated on the legend by phase and can be compared with the topographic 
features of the canyon itself. In short, this map allows a fast view of the Great House construction by phase.  This allows a temporal view of construction for 
building clusters in the canyon, hypothesizing why a Great House is located in a specific area.  You can annotate the stored base map to indicate the type 
of Great House (ritual, residence, storage, etc.) and adjacent structures.    

The creation of this map was accomplished in the following steps.  First, an appropriate map was selected from the XYZ Tile area of QGIS.  During this phase of 
development numerous maps were examined, including ESRI Standard, ESRI Satellite, ESRI Terrain, ESRI Topo World, ESRI National Geographic, and OpenStreetMap.  
These maps were eventually discarded after my determination that they needed more detail, needed to have the contrast required, or displayed too many 
roads/trails and not enough topographic features. After selecting the OpenTopoMap for the base, I selected the topographic level of view best suited to display 
the topographic and hydrologic detail I required. This area was georeferenced, utilizing the QGIC "georeferencing" tool, and a new layer was created. Points for 
the georeferencing step were taken from the corners of the Chaco Canyon Cultural Park boundaries, a part of the original base map.  This was done to ease 
annotation and overall map usage. The new annotation layer was created once the new layer was laid over the existing base map. At this point, the baseline map for 
Chaco Canyon was completed and can be used for future projects.  

<img src= "https://github.com/gwch223/Chaco_Canyon_Project/blob/main/Chaco%20Canyon%20Detail/Chaco_Canyon_modified.pdf" />

After the base map was configured, my next step was labeling locations within the canyon.  This required the activation of the "Annotation" toolbar.  Going 
to the main toolbar, under "View" and "Toolbar," I was able to activate this feature.  Once this was accomplished, I started by placing markers at the location of the 
Great Houses and other features of importance in the canyon that information come from the aforementioned archaeological texts.  Once these were placed, I labeled them with 
the Great House name and initial construction date.  

<img src= " "  />

I was not interested in subsequent construction on each Great House for this map, only the initial 
construction date and the phase within which that work was started. Later maps may have the range of construction date as a comparison.  In the labeling, I 
noted that the placement of the labels could have been more straightforward.  The text area was slightly offset from where I thought they would appear, so it took me 
a little time to locate the labels.  Once this was done, the next issue was the font size.  From one day to the next, the proximate siZe of the fonts changed so that what was 
a good font for viewing one day was too large the next day.  Again, a little trial and error allowed me to gauge the correct font size for the map.  Once the labeling 
was done, the map was ready for a print layout.  

<img src= " " />


The construction of the print layout was no problem, with the only minor issue being the selection of a background color for the page and a font color that would be easy
to read. Once this was done, the page was quickly rendered, and the final two .jpg prints (600 and 1200 dpi) were laid out.  

I started the project using the EPSG: 3857 projection regarding the scale and CRS information.  This seemed to work well at the 1:10000 scale, and the information was clear and 
readable.  I did examine the possible use of EPSG: 4269; however, this projection distorted the labels and some features of the georeferenced map, so I stayed with EPSG: 3857.  

Overall, this was a fun project and one which I can utilize in the future for quick map creating and utilization.
