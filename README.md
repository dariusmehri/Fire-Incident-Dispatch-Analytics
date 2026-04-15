# Fire Incident Dispatch Analytics

This project uses Python, generative AI, Power BI, and NYC Open Data to deliver data-driven insights into 2025 FDNY fire dispatch operations.

In 2025, FDNY dispatch responded to 211,775 incidents. Medical incidents accounted for more than half of all calls (108,948). The next most common categories were assist civilian (15,846), utility emergencies (15,012), alarm system activations (14,702), and elevator emergencies (14,702). Additional incident types included odors, non-medical calls, multiple dwelling incidents, vehicle accidents, and private dwelling fires.

This analysis aims to identify spatial hotspots for three incident types—medical, assist civilian, and private dwelling fires—across the city. Incident rates were normalized by population per 100,000 residents to enable meaningful comparisons, with results evaluated at the community district level.

### Medical Incidents
The analysis reveals two distinct patterns in medical incident rates across New York City. Midtown Manhattan emerges as the highest apparent hotspot; however, this is primarily driven by a mismatch between its large  daytime population and relatively small residential population, which inflates the population-normalized rate. In contrast, Bronx neighborhoods—including Melrose, Mott Haven, Morrisania, and Crotona Park East—as well as Brownsville in Brooklyn, represent true residential hotspots. These areas are characterized by high population density, socioeconomic vulnerability, and greater reliance on emergency services, resulting in genuinely elevated medical incident rates.


<img width="1135" height="642" alt="image" src="https://github.com/user-attachments/assets/8a02306b-385a-4f00-810b-c40a86b82b39" />


### Assist Civilian
The distribution of assist civilian incidents reveals a clear concentration in Bronx neighborhoods, including Melrose, Mott Haven, Morrisania, and surrounding areas. Unlike medical incidents, which are influenced by daytime population in commercial districts, assist civilian calls are more closely tied to residential vulnerability. These neighborhoods are characterized by high-density housing, significant NYCHA presence, and populations with greater mobility and health challenges. As a result, FDNY frequently serves as a primary support system for non-emergency assistance. Midtown Manhattan also ranks highly, but this is driven by high daytime population rather than underlying residential need. Central Harlem exhibits similar patterns to the Bronx, reflecting comparable socioeconomic and housing conditions.


<img width="1113" height="651" alt="image" src="https://github.com/user-attachments/assets/2eef750c-e356-460f-b23b-01b4440fc964" />


### Private Dwelling Fires


<img width="1150" height="656" alt="image" src="https://github.com/user-attachments/assets/0c99ac86-e0c2-45ff-a484-4b83642d52fd" />
