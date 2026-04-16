# Fire Incident Dispatch Analytics

This project uses Python, generative AI, Power BI, and NYC Open Data to deliver data-driven insights into 2025 FDNY fire dispatch operations.

In 2025, FDNY dispatch responded to 211,775 incidents across 39 incident types. Medical incidents accounted for more than half of all calls (108,948). The next most common categories were assist civilian (15,846), utility emergencies (15,012), alarm system activations (14,702), and elevator emergencies (14,702). Other incident types included odors, non-medical calls, multiple dwelling incidents, vehicle accidents, and private dwelling fires.

This analysis aims to identify spatial hotspots for three incident types—medical, assist civilian, and private dwelling fires—across the city. Incident rates were normalized by population per 100,000 residents to enable meaningful comparisons, with results evaluated at the community district level.

### Medical Incidents
The analysis reveals two distinct patterns in medical incident rates across New York City. Midtown Manhattan emerges as the highest apparent hotspot; however, this is primarily driven by a mismatch between its large  daytime population and relatively small residential population, which inflates the population-normalized rate. In contrast, Bronx neighborhoods—including Melrose, Mott Haven, Morrisania, and Crotona Park East—as well as Brownsville in Brooklyn, represent true residential hotspots. These areas are characterized by high population density, socioeconomic vulnerability, and greater reliance on emergency services, resulting in genuinely elevated medical incident rates.


<img width="1139" height="658" alt="image" src="https://github.com/user-attachments/assets/b2f81bef-0b7a-49f5-a48e-ec1d21f125b2" />




### Assist Civilian
The distribution of assist civilian incidents reveals a clear concentration in Bronx neighborhoods, including Melrose, Mott Haven, Morrisania, and surrounding areas. Unlike medical incidents, which are influenced by daytime population in commercial districts, assist civilian calls are more closely tied to residential vulnerability. These neighborhoods are characterized by high-density housing, significant NYCHA presence, and populations with greater mobility and health challenges. As a result, FDNY frequently serves as a primary support system for non-emergency assistance. Midtown Manhattan also ranks highly, but this is driven by high daytime population rather than underlying residential need. Central Harlem exhibits similar patterns to the Bronx, reflecting comparable socioeconomic and housing conditions.


<img width="1129" height="662" alt="image" src="https://github.com/user-attachments/assets/9bd99a2d-7251-4279-8460-cb38d9820b79" />



### Private Dwelling Fires
The distribution of private dwelling fire incidents is concentrated in Queens, Staten Island, and parts of Brooklyn, reflecting the prevalence of low-rise, one- and two-family homes in these areas. Unlike other incident types, which are driven by population density or socioeconomic factors, private dwelling fires are closely tied to housing characteristics, including building type, age, and heating systems. As a result, neighborhoods with a higher proportion of private homes—such as Queens Village, Rosedale, and Tottenville—exhibit elevated incident rates. In contrast, denser areas of Manhattan and the Bronx, which are dominated by multi-family apartment buildings, show lower rates for this specific category, as fires in those areas are more likely classified under multiple dwelling incidents.

<img width="1149" height="655" alt="image" src="https://github.com/user-attachments/assets/0c0b1980-7421-4803-ac67-fdbcbc0f196e" />

### Response Time
Response time analysis for all incidents reveals a clear geographic concentration of slower performance in the Bronx, with eight of the ten highest-response-time districts located there. While overall response times are tightly distributed around a six-minute average, these districts consistently exceed that baseline. The pattern is likely driven primarily by operational factors, including high call volume, reduced unit availability, and challenging street conditions such as congestion and narrow roadways. As a result, responding units are more frequently dispatched from greater distances, increasing travel time. Similar, though less pronounced, patterns are observed in dense areas such as Astoria and the Upper East Side.

<img width="1131" height="651" alt="image" src="https://github.com/user-attachments/assets/26e6028b-31c7-4ded-a2cf-28daa8c1bb48" />



#### Response Time Outlier Analysis
Response times for all incidents average 6.08 minutes (standard deviation: 0.60 minutes). The histogram shows the distribution of response times, highlighting a concentration of higher values in the Bronx, while the map identifies community districts exceeding one standard deviation above the mean.

<img width="919" height="679" alt="image" src="https://github.com/user-attachments/assets/90e5e475-5510-4026-bd56-c77cc72074e2" />


<img width="819" height="632" alt="image" src="https://github.com/user-attachments/assets/bf32b9f0-001a-4cb0-b4fd-ad7923b8eb37" />










