<body>
<h1>Wikipedia_US_cities_scraping_python<h1>

<p>The notebook scrape Wikipedia in order to find information about the biggest cities in the US</p>

<h2>First part:</h2>
I start by scraping the wikipedia page: https://en.wikipedia.org/wiki/List_of_United_States_cities_by_population \n
which contain informations about the 314 most populated cities in the US

### Second part:
I go through the wikipedia pages of all the 314 cities listed in the previous link.

### Data description:
2018_rank: (Integer) Rank the cities by population size\n
City: (String) Name of the city\n
State: (String) City's state\n
2018_estimate: (Integer) Population estimated in 2018\n
2010_census: (Integer) Population in 2010\n
Change (%): (float) Percentage of change between 2010 and 2018\n
2016_land_area (km2): (float) land area in 2016 in squared km\n
2016_density: (Integer) Population density in 2016\n
Location: (String) Latitude and Longitude\n
Description: (String) City's description from Wikipedia\n
Nickname: (String) City's nickname(s)\n
County: (String) Name the counties included in the city or the county in which the city is included\n
Govern_type: (String) Give the type of government of the city\n
Govern_body: (String) Constitution of the city government\n
Govern_mayor: (String) City's mayor\n
Area_land: (String) Land area in squared miles and squared km\n
Area_water: (String) Water area in squared miles and squared km\n
Area_metro: (String) Metro area in squared miles and squared km\n
Elevation: (String) Elevation in ft and m\n
CSA: (float) CSA\n
Time_zone: (String) Time zone\n
ZIP_code: (String) ZIP codes included in the city\n
Area_code: (String) Area code in the city\n
FIPS_code: (String) FIPS code\n
Airport: (String) List of airports in the city\n
Website: (String) City's official website\n
Area_land (km2): (float) land area in squared km\n
Area_water (km2): (float) water area in squared km\n
Area_metro (km2): (float) Metro area in squared km\n
Elevation (m): (float) Elevation in m\n
