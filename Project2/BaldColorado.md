## The Relationship Between Fish Presence and Bald Eagle Nests in Colorado

<img src="../images/baldbanner.jpg?raw=true"/>

**Project description:** This project consists of maps and R code presenting the relationship between Bald Eagle nests and Fish Presence in Colorado. In this project, maps of the fish presence and bald eagle nests were made to visually show the spread of areas throughout the state. R code was used to make 1 km buffers around the Eagle Nest file and show the intersections with fish presence throughout the state. The data was collected from the Colorado Government GIS Website.

## Bald Eagles Nests

<img src="../images/BaldEagleFinal12.jpg?raw=true"/>

  This Figure shows that Bald Eagle Nests are spread out throughout the entire state. The area with the highest presence shown in the Heatmap to the left is near the Denver area. This area is more populated but ultimatley leads to the edge of the Rocky Mountains. This area has the highest Eagle Nest population in the country. Each Nest does have conditions associated to it. The colors reppresent whether the nest is Active, Destroyed, Inactive, Undetermined, or Unknown. These conditions are shown throughout the entire state. As you can see from the figure, most of the nests throughout the state are either Active or Unknown.

## Fish Presence

<img src="../images/ColoradoFishFinal.jpg?raw=true"/>

  Colordo has many different species of fish within its water. In this study we studied the presence of five different species throughout the state. The Stonecat, Common Shiner, Mountain Sucker, Orange Throat Darter, and the Blue head Sucker. The Figure above shows the presence throughout the state of the different species.
  
  ## R Methods
  
  For the R portion of this project I made 1 km buffers around each Bald Eagle nest to show a range of where the Eagle would fly within the range of the nest. I then found where the bald eagle nests intersected with the buffers. These intersections would show which bald Eagles intersected with the different Species.
  
  Below are the Intersection points for all five species of fish:
  
  ###### Bald Eagle Nest Intersection Points
  <img src="../images/AllFish.jpg?raw=true"/>
  
  This shows many intersections leading to belive that as you would expect Eagle nests are closer to areas of fish presence. Two Fish showed great amounts of intersection including the Mountain Sucker and the Blueheaded Sucker.
  
  Below are the Respective maps for each species intersections:
  
###### Mountain Sucker Intersection Points
  <img src="../images/MountainFishFinal.jpg?raw=true"/>
  
###### Blueheaded Sucker Intersection Points
  <img src="../images/Blueheaded.jpg?raw=true"/>
  
  The Intersection Points ultimately told us the condition of each Eagle Nest that Intersected. As you can see from the figure below, most of the Eagle Nests apeared to be active in the areas of fish presence. This shows that not only do Eagle nests correlate closely with Fish Presence but secifically active Eagle Nests.
  
###### Activity Condition of Intersecting Eagle Nests
 <img src="../images/graph.JPG?raw=true"/>
 
###### Bald Eagle Fish Species Web Map
 
  The web mapp shows the different aspepcts of the Bald Eagle nests and Fish Presence. Also involves a choropleth map showing the abundance of bald eagle nests per county.
  [Bald Eagle Fish presence WEBMAP](/qgis2web_2020_04_23-13_02_30_659492)
  
  ##### Nearest Neighbor Calulations
  
  Nearest Neighbor Calculations were done on the different fish species to find which fish species was most correlated to the Bald Eagle nests. Each Fish polygon was converted to an sf object and the nearest neighbor calculation was conducted to show the distance form the eagle nests to the areas of fish. The averages were then calculated to find the fish that spaptially correlated most with the Bald Eagle nests. 
  
  The fish species that most correlated with Bald Eagle nests was the Stone Cat species. This makes sense due to the fact that although it is a small area they were closely related to the area of high eagle population.
  <img src="../images/stone.jpg?raw=true"/>
  
  

  
  
  
  

