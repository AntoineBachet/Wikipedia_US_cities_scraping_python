<body>
  <h1>Wikipedia_US_cities_scraping_python</h1>

  <p>The notebook scrape Wikipedia in order to find information about the biggest cities in the US</p>
  <div>
    <h2>First part:</h2>
    <p>I start by scraping the wikipedia page: https://en.wikipedia.org/wiki/List_of_United_States_cities_by_population</p>
    <p>which contain informations about the 314 most populated cities in the US</p>
  </div>
  <div>
    <h2>Second part:</h2>
    <p>I go through the wikipedia pages of all the 314 cities listed in the previous link.</p>
  </div>
  <div>
    <h2>Python Libraries:</h2>
    <p>To run this module you need the following libraries:</p>
    <ul>
      <li>Pandas</li>
      <li>Numpy</li>
      <li>requests</li>
      <li>bs4</li>
      <li>re</li>
      <li>time</li>
    </ul>
  </div>
  <div>
    <h2>Data description:</h2>
    <p>2018_rank: (Integer) Rank the cities by population size</p>
    <p>City: (String) Name of the city</p>
    <p>State: (String) City's state</p>
    <p>2018_estimate: (Integer) Population estimated in 2018</p>
    <p>2010_census: (Integer) Population in 2010</p>
    <p>Change (%): (float) Percentage of change between 2010 and 2018</p>
    <p>2016_land_area (km2): (float) land area in 2016 in squared km</p>
    <p>2016_density: (Integer) Population density in 2016</p>
    <p>Location: (String) Latitude and Longitude</p>
    <p>Description: (String) City's description from Wikipedia</p>
    <p>Nickname: (String) City's nickname(s)</p>
    <p>County: (String) Name the counties included in the city or the county in which the city is included</p>
    <p>Govern_type: (String) Give the type of government of the city</p>
    <p>Govern_body: (String) Constitution of the city government</p>
    <p>Govern_mayor: (String) City's mayor</p>
    <p>Area_land: (String) Land area in squared miles and squared km</p>
    <p>Area_water: (String) Water area in squared miles and squared km</p>
    <p>Area_metro: (String) Metro area in squared miles and squared km</p>
    <p>Elevation: (String) Elevation in ft and m</p>
    <p>CSA: (float) CSA</p>
    <p>Time_zone: (String) Time zone</p>
    <p>ZIP_code: (String) ZIP codes included in the city</p>
    <p>Area_code: (String) Area code in the city</p>
    <p>FIPS_code: (String) FIPS code</p>
    <p>Airport: (String) List of airports in the city</p>
    <p>Website: (String) City's official website</p>
    <p>Area_land (km2): (float) land area in squared km</p>
    <p>Area_water (km2): (float) water area in squared km</p>
    <p>Area_metro (km2): (float) Metro area in squared km</p>
    <p>Elevation (m): (float) Elevation in m</p>
  </div>
</body>
