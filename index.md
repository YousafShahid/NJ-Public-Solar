# Installed Solar capacity and energy consumption comparison between counties of the State of New Jersey<br/>
#### Muhammad Yousaf Shahid, EJB School of planning and public policy, Rutgers University.

This spatial analysis aims to evaluate and compare the solar capacity deployment and energy consumption per 10,000 residents across different counties in the state of New Jersey, United States. This analysis is used to access highest solar adoption rates between states.
The analysis and associated maps are created by Muhammad Yousaf Shahid, as the final project for the course command line offered as a part of the Master of Public Informatics program at the Rutgers University Edward J. Bloustein School of Planning and Public Policy.

## STATIC MAPS

### SOLAR INSTALLED CAPACITY 

<iframe src="SOLAR_CAPACITY.png" width = "600" height = "1020"></iframe><br/>

### TOTAL ENERGY CONSUMPTION

<iframe src="Energy_Consumption.png" width = "600" height = "1020"></iframe><br/>

### NJ INCOME PER CAPITA

<iframe src="NJ_INCOME PER CAPITA.png" width = "600" height = "1020"></iframe><br/>

### NJ COMMUNITY SOLAR PROJECTS 

<iframe src="COMMUNITY_SOLAR.png" width = "600" height = "1020"></iframe><br/>



### INTERACTIVE MAPS

<iframe src="NJ_COMMUNITY_SOLAR.html" width = "1020" height = "905"></iframe><br/>

You can also explore [this map as its own web page here](NJ_COMMUNITY_SOLAR.html)


### CONCLUSION
From the maps, it can be concluded that Somerset is the only county with the highest bracket of installed solar generation per 10,000 residents, and in terms of energy consumption Essex and Bergen counties has the highest energy consumption per 10,000 residents. Therefore it can be concluded that Somerset has the highest solar share in its total energy consumption, suggesting strong solar PV adoption compared to all other states.

Cape may, Atlantic, and Cumberland have the least energy consumption per 10,000 residents and the lowest solar penetration. 
It is worth noticing that the highest income per capita states are not leading energy consumption among all states. This is indicative that energy consumption is not solely driven by economic activity but depends on other influential factors.

Community solar projects were also explored to see how community solar projects are located throughout New Jersey. it has been observed that Burlington and Ocean County have the highest community solar potential. This reason for this can be reflected as Burlington and Ocean County are the top two in terms of area and among the lowest for population density which means more potential for solar infrastructure. However, no community solar project was reported for Sussex and Hunterdon counties which clearly indicates that all of the solar in those two counties are either private or public solar facilities, making it a prime location for the introduction of community solar projects through which these counties can amplify solar generation.


### DATA DESCRIPTION

The following data sets are used to create these maps:

Solar Photovoltaic (PV) Installations by County in New Jersey acquired from NJGIN open data portal Source: [PV Installations ](https://njogis-newjersey.opendata.arcgis.com/datasets/e3366d6efe9b4b3286db54d63c41ef6a_15/explore), This data set provides information on total installed solar PV capacity by each county. This has been useful to spatially analyze solar energy generation in comparison to total energy consumption. The initial observed unit was Kilowatt (KW) which we have converted into MegaWatt (MW).The data was initially in csv format which was aggregated with NJ counties shape file for mapping purposes. The data set was converted into EPSG 3424 for mapping purposes. The data has no missing or null values. The data set was recently updated on 6/21/2023.

Municipal Energy Use in New Jersey acquired from NJGIN open data portal Source: [Municipal Energy Use ](https://njogis-newjersey.opendata.arcgis.com/maps/c7fac4b6308749f2baa94e87fe4be22e), This data set provides annual energy consumption for the municipalities of New Jersey. From this data, we have calculated county-wise spot energy consumption from annual energy consumption for comaprison with installed solar capacity. The unit of measurement was initially KiloWatt (KW) which for our analysis is converted into MegaWatt (WM).The data was initially in CSV format which was aggregated with NJ counties shape file for mapping purposes.

New Jersey Community Solar PV Projects acquired from NJGIN open data portal Source: [Community Solar](https://njogis-newjersey.opendata.arcgis.com/datasets/dfa1235ba73b4ff999cc6500647b45a6_26/explore), This data set has been utilized to map community solar projects and provide information for future potential opportunities for solar growth projects. The data was aggregated with NJ counties shape file for mapping purposes. The data was spatially joined from point to ploygon with NJ counties shape file for static mapping for NJ community solar projects. Missing values were shaded with // on the map.

Population and income data sets have been acquired  from acs survey through census API Source: [CENSUS](https://www.census.gov/programs-surveys/acs/data.html). These data sets have been used to calculate solar generation per 10,000 residents and energy consumption per 10,000 residents. Income per capita is used to conclude the energy consumption trend between counties.



