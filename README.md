Chaco_Canyon_Project (Building Phases)
This project was constructed utilizing tile basemaps from OpenTopoMap (https://opentopomap.org/#map=9/38.3524/-105.8835).  This map was downloaded as part of XYZ Tiles utilizing QGIS 3.38 Grenoble software. 
Annotation data was taken from the books, "Archaeology and Archaeologists: Chaco Canyon," by Robert H. Lister & Forence C. Lister, 
and "The Chaco Canyon Handbook: An Encyclopedic Guide," by R. Gwinn Vivian & Bruce Hilpert.  

This map was created to be the basemap for a multi-phase project to depict differing areas of Chaco Canyon and the location of Great Houses, water sources,
andother features not normally found, or difficult to compile, from other sources.  Specifically, this map shows the location of Great Houses within Chaco Canyon 
with annotations to their initial construction year.  These construction periods are annotated on the legend by phase and can be compared with the topographic 
features of the canyon itself. In sort, this map allows a fast view of Great House construction by phase.  This allows a temporal view of construction for 
building clusters in the canyon, generating hypothesis as to why a Great House is located in a specific area.  Additional annotation can be made, as required,
to the stored base map to indicate the type of Great House (ritual, residence, storage, etc.) and adjacent structures.    

The creation of this map was accomplished in the following steps.  First an appropriate map was selected from the XYZ Tile area of QGIS.  During this phase of 
development numerous maps were examined, including ESRI Standard, ESRI Satellite, ESRI Terrain, ESRI Topo World, ESRI National Geographic, and OpenStreetMap.  
These maps were eventually discarded after my determination that they did not have sufficient detail, did not have the contrast required, or displayed too many 
roads/trails, and not enough topographic features. After selecting the OpenTopoMap for the base, I selected the topographic level of view best suited to display 
the topographic and hydrologic detail I required. This area was the georeferenced, utilizing the QGIC "georeferencing" tool,  and a new layer created. Points for 
the georeferencing step were taken from the cornors of the Chaco Canyon Cultural Park bondaries which are a part of the original basemap.  This was done to ease 
annotation and overall map usage. Once the new layer was layed over the existing basemap, the new annotation layer was created. At this point the baseline map for 
Chaco Canyon was completed and can be used for future projects.  

<img src= "https://github.com/gwch223/Chaco_Canyon_Project/blob/main/Chaco%20Canyon%20Detail/Chaco_Canyon_modified.pdf" />

After the basemap was configured my next step was the labeling of locations within the canyon.  This required the axctivation of the "Annotation" toolbar.  Going 
to the main toolbar, under "View" and "Toolbar" I was able to activate this feature.  Once this was accomplished I started by placing markers at the location of the 
Great Houses and other features of importance in the canyon, that information coming from the afformentioned archaeological texts.  Once these were placed I started 
labeling with Great House name and initial construction date.  For this map I was not interested in subsequent construction on each Great House, only the initial 
construction date and the phase within which that work was started. Later maps may have the range of construction date as a comparison.  In doing the labeling I 
noted that the placement of the labels was tricky.  The text area was a bit offset from the area I thought they would appear at, so it took me a little time to get the
hang of locating the labels.  Once this was done, the next issue was the font size.  From one day to the next the proximate siZe of the fonts changed so that what was 
a good font for viewing one day was too large the next day.  Again, a little trial and error allowed me to gage the correct font size for the map.  Once the labeling 
was done the map was ready for a print layout.  

The construction of the print layout was no problem with the only small issue being the selection of a background color for the page and a font color which would be easy
to read. Once this was done the page was quickly rendered and the final two .jpg prints (600 dpi and 1200 dpi) were laid out.  

Regarding the scale and CRS information, I started the project using the EPSG: 3857 projection.  This seemed to work well at 1:10000 scale and the information was clear and readable.  I did examine the possible use of EPSG: 4269, however, this projection distorted the labels and some features of the georeferenced map, so I stayed with EPSG: 3857.  

Overall, this was a fun project and one which I can utilize in the future for quick map creating and utilization.
