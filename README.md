# Final Project: NFL GIS Application
**Student:** Emily Phan, phancy@uw.edu

**Quarter:** Autumn 2021

After taking an 11-week course in Web & Mobile GIS at the University of Washington, I create my own application as part of my final project. In my final project, I decided to create a web GIS application that locates all 32 of the National Football League (NFL) team’s stadiums in the United States. Each location shows the stadium name with the NFL home team name and the capacity it holds. 
The goal of this application is to allow users to be able to locate all of the football stadiums used in the NFL and to check its capacity, as well as see which team belongs to which state and stadium. This map also gives users a geographic visualization which allows them to see how the NFL is laid out throughout the United States. 

Application URL: https://emilyphantastic.github.io/Final-Web-GIS-App 

![fullapp](img/fullapp.png)

The main function of this application allows users to either click on the NFL logo icons to see which stadium is located in the area, or they can use the side-bar menu to click through specific stadiums they want to get more information on.


The side-panel allows users to scroll through the list of the 32 NFL teams in the United States in alphabetical order. Note that there are two NFL teams that play in the SoFi Stadium in Los Angeles and two teams play in the MetLife Stadium in New Jersey (5 miles west of New York City). 

![side](img/side-panel.png)

On the main map, you are able to see a street view visualization of the United States. Zoomed out, it shows green outline of the United States surrounded by other nearby countries and bodies of water (outlined in blue). 
![map-only](img/map-zoom-out.png)

As you manually zoom into a stadium, click an NFL logo, or use the side-panel to click on a stadium’s name, the map will zoom in deeper into the map until you are able to see a street view. With the street view you are able to see surrounding streets of the stadium as well as nearby businesses and parks. There is also a pop-up that labels the stadium’s name and highlights it’s capacity. This way you can remember what stadium you are currently examining. 

![street-view](img/street-view.png)

You can also drag and scroll away from the stadium to explore other parts of the area away from the stadium itself. 
![drag](img/street-view-two.png)

The data I used was data I found by researching. I created my data by first researching the NFL stadiums in the United States then manually plugging all of the information and coordinates I find into a JSON file. I then use a fetch function in the HTML files to ready my data. 
I found the NFL logo through a Google search and used an online PNG tool to resize my logo to my desire. 
## Applied Libraries
- [Mapbox Studio](https://studio.mapbox.com/)
- [GitHub]( https://github.com/)
- [Mapbox GLJS]( https://docs.mapbox.com/mapbox-gl-js/api/)
- [Mapbox Streets Style]( mapbox://styles/mapbox/streets-v11)

## References/Data Sources:
- [NFL logo]( https://en.wikipedia.org/wiki/National_Football_League)
- [NFL teams](https://www.nfl.com/teams/)
- [NFL team stadiums and capacity](https://geojango.com/pages/list-of-nfl-teams)
- [NFL color scheme](https://www.schemecolor.com/national-football-league-nfl-logo-colors.php)
- [Online PNG tool](https://onlinepngtools.com/resize-png)

## Acknowledgement:
- [GEOG 495](https://github.com/jakobzhao/geog495/tree/main/modules/module07)
- [MapBox](https://www.mapbox.com/)
- [GeoJSON]( https://geojson.io/#map=2/20.0/0.0)
- [National Football League](https://www.nfl.com/)
