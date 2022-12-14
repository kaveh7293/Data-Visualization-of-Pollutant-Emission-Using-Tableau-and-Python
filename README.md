# Data-Visualization-of-Pollutant-Emission-Using-Tableau and Python
<h2>Overview</h2>
<p> In this project, I used Tableau to visualize the data describing the Air Polution in different countries all around the world. The dataset that is used was downloaded from <a href='https://www.kaggle.com/datasets/hasibalmuzdadid/global-air-pollution-dataset'> here</a>. This dataset contains information about the concentration of different pollutant species within the air (e.g., carbon monoxide and ozone). </p><br>
<h2>NO2 AQI</h2>
<p> In the following figure the countries whose AQI is greater than 5 is shown:<br><br>
<img src='https://github.com/kaveh7293/Data-Visualization-of-Olympic-Data-Using-Tableau/blob/main/NO2_index_greater_than5.png'><br>
As can be seen South Korea, USA, China, Algeria, South Africa, Mexico, Costa Rica, Dominican Republic and Chile have hire NO2 AQI compared to the rest of the world. In this figure, the countries with NO2 AQI of greater than 5 are filtered to be colored and the rest of countries were not indicated with any color. In the following figures, the plots of CO and Ozone AQI are also shown, respectively:<br>
<img src='https://github.com/kaveh7293/Data-Visualization-of-Olympic-Data-Using-Tableau/blob/main/CO_index_greater_than5.png'><br>
<img src='https://github.com/kaveh7293/Data-Visualization-of-Olympic-Data-Using-Tableau/blob/main/Ozone.png'><br>
The countries with larger CO and Ozone emissions are USA, China, Algeria, South Africa, Korea, Dominican Republic, Costa Rica and Chile.

</p><br>
<p> Finally, I did a PCA dimension reduction followed by a biplot to see which features mostly distinguish the cities in the world in terms of pollutant emission.
  I chose three principal components, as the first three components describes 95% of the variability in the data. The first two principal components describe 80% of variation in the data:<br>
  <img src='https://github.com/kaveh7293/Data-Visualization-of-Olympic-Data-Using-Tableau/blob/main/pc_variability.png'><br>
  As shown, only a few cities in the world have high emissions of CO and NO2 (see the upper right corner of the t1 vs. t2 plot). Most of the cities in the world have no significant production (e.g., see the green cluster in the center of the figures):<br>
<img src='https://github.com/kaveh7293/Data-Visualization-of-Olympic-Data-Using-Tableau/blob/main/t1_t2.png'><br>

  Based on the clustering analysis, the cities in the red cluster have higher ozone production. People within the same clusters should probably follow smilar policies in order to reduce their emissions. Doing this cluster analysis could help countries with the same problem to gather and work together in order to solver this important environmental problems more efficiently. The code for these implementations can be found <a href='https://github.com/kaveh7293/Data-Visualization-of-Pollutant-Emission-Using-Tableau-and-Python/blob/main/Pollution.ipynb'> here </a>.

</p>

