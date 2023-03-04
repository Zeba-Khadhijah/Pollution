# Analysis of the Pollution Inventory 2021

The Pollution inventory dataset collates information on (i) Annual mass releases of emissions to air, 
controlled waters and sewers,(ii) Waste transfers,(iii) Radioactive waste emissions. This dataset covers sites in England for 2021 and can be freely accessed from:
https://environment.data.gov.uk/portalstg/home/item.html?id=7ddf166a9b41444ebdca1baec1eede38 
The present project only uses the annual emissions to air water and sewers data.

### Motivation for choice of project:
I have been inclined towards environmental causes since I was a teenager. Seeing how urgent it is to mitigate the climate crisis, I want my work to be a part of the solution. We need to find sustainable methods to fight global warming and I believe that somewhere in the large amount of data we generate, lies creative sustainable solutions.
Analysis provides insights on which industries and industrial activities pollute more, which pollutants are released in largest quantities, which route of emmission is most common, and the geographic distribution of the polluting industries across the country. These findings can have implications in environmental policy making to meet sustatainable development goals.

The following libraries were used for data analysis:
•	Pandas: Used for data analysis and cleaning using data frames
•	Numpy: Used for fast array processing where pandas series is converted into numpy array
•	Matplotlib: Used for Visualization
•	Seaborn: Used for Visualization
•	Convertbng: Used to convert easting and northing into longitude and latitude
•	Geopandas: Used to plot geograph where bubble plot is applied on UK Map
•	Shapely: Used to convert Longitude and Latitude data into point form for geopandas
•	Sklearn: Used to import minmax scaler
•	Scipy: Used for statistical analysis (chi square statistic)

Setup for UK Map using Geopandas:
UK Map shape files are put in a folder named geo_shape and imported to read points for plotting UK Map for visualizations.
