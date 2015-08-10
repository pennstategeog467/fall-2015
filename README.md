# GEOG 467, Fall 2015
Project ideas for the Fall 2015 semester of GEOG 467: Applied Cartographic Design
### Projects

- [FixWikiMaps](http://fixwikimaps.tumblr.com/)
- [Pop-Carte] (http://pennstategeog467.github.io/pop-carte/)
- OSM for Surrounding Communities 
  - Lemont, Houserville, Boalsburg, Park Forest, Pine Grove Mills

### Penn State Online Campus Map

**OpenStreetMap Editing**
- Sidewalks "May require field work" 
- Athletic & IM fields
- Downtown Buisnesses

**PSU Data**
 - Trees
 - Roofline Details
  - Roof-lines are not specific to each building
  - Work with OPP on adding building attribute to roof-line detail
  - Needed for emplementing Building Heights
 - Implement Building Heights
  - Use existing height information to give buildings a relative height
  - Transform Roof-line details to match relative building heights

**Online Map**
 - Directions
  - Add a starting place option
  - Options for driving/bicycle/walking
 - Live Cata Bus Locations/Routes
 - Parking
  - Everyday student/staff/visitor parking
  - Event specific parking ie. Football
 - Transition between Day&Night Map
  - By click of button or time of day
  - Update night map styles to match the day map
 - Bicycle Information
  - Racks/ServiceStations/Shops
 - Penn State Branding
  - New logo/word mark
  - Nittany Lion
  - Campus Label
  - Universiy Park Designation
 - BackUp OSM Basemap
   - For rare occasions when Mapbox goes offline
   - Example [Aug 10th 2015] (https://cloud.githubusercontent.com/assets/11635991/9181765/c8257e9e-3f74-11e5-87f0-065b622be8a6.PNG)


**Campus Map Editor**
 - Web Based Backend Editor
   - Used to maintain campus map data such as:
     - Campus building information for pop-ups
     - Campus construction overlays
     - Any additional campus json data
   - Ability to:
     - Load data files from github repo
     - Create and Edit data through a GUI
     - Save directly to github repo 
   - Editor Map
     - PennState 467 Map
     - OPP 2012 Satellite
