# Airport Passenger Traffic Analysis
## A mechanic exploration of factors correlated to airport passenger traffic.
![alt text](https://github.com/AdamPeetz/PassengerTrafficAnalysis/blob/main/EquirectangularOverlay.jpg) <br>

### Factors contributing to passenger traffic: An exploration of correlating variables

3 factors that impact airport passenger traffic are demand, connectivity, and competition. The demand for airline travel is based on business and leisure spending. More money available for these pursuits drives higher volumes of traffic through local airports. Passenger traffic is also based on the number of connections an airport has. Airports with many connections serve as hubs to smaller regional airports. Passenger count is also impacted by competition from nearby airports. An airport may have potential passengers served by a nearby neighbor. (Rodrigue, 2020) The purpose of this paper is a mechanic exploration of the factors impacting passenger traffic. It will prove the correlation between these variables, with discussion focused on the 5 busiest airports.

### Five Busiest Airports

Passenger traffic is defined for each airport by the number of passengers boarded and deplaned. The busiest airports in the world are Hartsfield-Jackson in Atlanta, which serviced over 104 million passengers, followed by Beijing, Dubai, Los Angeles, and Tokyo. These five airports will be used to guide the discussion in the remainder of the report.

![alt text](https://github.com/AdamPeetz/PassengerTrafficAnalysis/blob/main/Top5Barchart.jpg) <br>

### GDP

Airline traffic is driven by business and leisure travel. One measure that can assess the amount of money available for this type of spending is a countries’ GDP. Countries with a higher GPD should have more business travelers and money to spend on tourism. A scatterplot with a trendline, shown below, displays the correlation between GPD and passenger traffic for the 50 busiest airports in the world. <br>

An interesting trend emerges when plotting traffic by GDP. It shows many of the busiest airports belong to a few countries with high GPD. The United States has 17 of the top 50 airports, China has 7. These juggernauts dominate this chart. One country and airport combination that does not fit this trend is Dubai in the United Arab Emirates. Dubai has high traffic but a comparably low GDP. This may be explained by the fact that Dubai is notorious for its luxury and spending.  Dubai is also the headquarters of Emirates Airlines, a major global carrier.

![alt text](https://github.com/AdamPeetz/PassengerTrafficAnalysis/blob/main/GDPPassengerScatter.jpg) <br>

### Connectivity

Connectivity is another factor that impacts passenger traffic. Airports with many connections serve as hubs between other large airports and to smaller regional airports. Plotting the number of connections each airport has against their passenger traffic reveals a strong correlation between these two variables. The airport with the most connections is Frankfurt in Germany, which connects to 238 other airports. An outlier here is Haneda airport in Tokyo, the 5th busiest airport, with only 74 connections. This may be explained by the city of Tokyo itself. Tokyo is the largest city in the world. It contains 39 million people. Japan also had the 3rd highest GDP, which is correlated to increased airline traffic.

![alt text](https://github.com/AdamPeetz/PassengerTrafficAnalysis/blob/main/ConnectivityPassengerScatter.jpg) <br>

### Geographic Connectivity

Airport connectivity isn’t just about numbers. Its geographic placement and distance. This type of connectivity can be visualized using a network graph. This plotting technique shows the reach these 5 airports have. With these 5 airports, or a transfer between them, you can reach almost anywhere on the globe. This view also shows the dominance of the northern hemisphere in air travel. There are fewer airline connections made to the southern hemisphere. 

![alt text](https://github.com/AdamPeetz/PassengerTrafficAnalysis/blob/main/ConnectivityNetworkGraph.jpg) <br>

### Competition

Competition has an adverse effect on the number of passengers an airport serves. An example of this is Haneda (HND) and Narita (NRT) in Tokyo. These airports are about 80km apart and share connections with 34 destination airports including major hubs like LAX, ATL, DXB, and PEK. They are ranked #5 and #48 in passenger travel and served a combined 118.6 million people. If a single airport served the city of Tokyo, it would be the busiest airport in the world.  

![alt text](https://github.com/AdamPeetz/PassengerTrafficAnalysis/blob/main/CompetitionVisual.jpg) <br>

### Conclusion

Passenger traffic at an airport is influenced by a combination of GDP, connectivity, and competition. GDP is strongly linked to passenger traffic. This is demonstrated by a few countries with high GDP that have multiple airports in the list of the top 50. Connectivity also shows a strong relationship. Flights can be booked to any section of the globe from the top five airports in the dataset. Geographic connectivity also shows that most of the airports in the world are concentrated in the northern hemisphere. Competition also had an effect, as demonstrated by the passenger shares of Haneda and Narita in Tokyo.  These three factors combine to influence passenger numbers moving through an airport.


