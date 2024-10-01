# Project-TIL6022---Group-2

Ideeen: 
1) Exploring the Impact of Remote Work on Public Transport Usage in the Netherlands
2) Evaluating the Impact of COVID-19 on Cycling Trends in the Netherlands
3) A Comparative Study of Pre- and Post-COVID Travel Behavior
4) De invloed van de oorlog in Oekraïne op handel / armoede / transport / routes in Oost-Europese landen
5) De invloed van de Brexit op transport (vliegtuigen?)  tussen EU landen en VK
6) Voorspellen vertraging van vlucht op basis van de weersomstandigheden op aankomst en vertrek locatie
7) Invloed van weer op vertraging van vluchten

Idea: The impact of weather conditions on flight delays / predict future delays for upcoming week. 
- Chose one specific flight (example: Amsterdam from/to New York).  
- Get data from delays of that flight
Constraints: 1 airline company & look only at weather conditions at arrival / destination (not in between)
Idea: different companies / drukte op vliegvelden

Data die we nodig hebben:
- weersomstandigheden in stad van vertrek en aankomst
- vluchtdata: vertragingen voor een specifieke vlucht

- voorbeeld data: vluchten 2013 https://www.kaggle.com/datasets/mahoora00135/flights?resource=download
- https://www.transtats.bts.gov/ONTIME/OriginDestination.aspx [ALLEEN AMERIKA]
- 


bronnen: 
https://www.transtats.bts.gov/ONTIME/OriginDestination.aspx
https://opensky-network.org/

should look at:

Temperature
Wind speed and direction
Precipitation
Visibility
Cloud cover
Weather events (storms, snow, fog, etc.)

data voor weer: 
https://meteostat.net/nl/#google_vignette
https://en.climate-data.org/


dit vond ik op een website: https://atmdata.github.io/sources/
voor vluchten moeten een account aanmaken:https://www.eurocontrol.int/dashboard/rnd-data-archive voor binnen Europa

Flight (or schedule) data
The following websites provides access to flight data, usually contains the origin, destination, number of passengers or aircraft information

🇺🇸 Bureau of Transportation Statistics (T-100 Segment, All Carriers). This table combines domestic and international T-100 segment data reported by U.S. and foreign air carriers, and contains non-stop segment data by aircraft type and service class for transported passengers, freight and mail, available capacity, scheduled departures, departures performed, aircraft hours, and load factor.
🇪🇺 Aviation Data for Research contains all detailed flight information regarding flight departing and/or arriving from EUROCONTROL member states. The data is only publish with two-year delay and only include four months each year, which are March, June, September, and December. Access to this data need to be requested on the website.
🇧🇷 Dados Estatísticos, Agência Nacional de Aviação Civil (ANAC), Brazil provides all flight information departing from and/or arriving at Brazil since 2000
🇮🇳 Flight Schedule Date, India contains the data regarding from AirSewa data, including data about the flight schedule, status, and airport services.
🇦🇺 Aviation Statistics, Australia contains domestic and international aviation statistics including airline activity, domestic on time performance, domestic airfares index, airfreight, airport traffic, general aviation activity, aviation fuel sales and air distances.
🇭🇰 Flight Information, Hong Kong contains flight Information of Hong Kong International Airport, including data about the flight schedule, status, passenger/cargo flight. This web service returns historical data (previous calendar day) in JSON format.

The following websites provide a large history of METAR data.
METARs report basic weather information around airports:

http://www.ogimet.com/index.phtml.en
https://mesonet.agron.iastate.edu/request/download.phtml
https://aviationweather.gov/dataserver
https://navlost.eu/
The following website provides METAR, TAF and SIGMET history:

http://www.aviationwxchartsarchive.com/product/sigmet
