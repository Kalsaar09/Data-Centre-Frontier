# Data-Centre-Frontier
GovHack 2025 Project for the challenge, Data Centres: A Cornerstone of Australia's AI Future.
Team Lead Kessler 
Team Members 
Kessler and Xingchen

Data Centre Frontier is a planning platform that turns complex site due diligence into clear, defensible decisions. Users draw a prospective data centre footprint and receive an immediate viability score with full breakdowns across electrical infrastructure, terrestrial and submarine telecoms, environmental hazards, climate, population and land-use zoning, and geological/topographic constraints. Using AI models and auditable datasets, the software also forecasts power and water demand, operating costs, and resilience trade-offs, enabling apples-to-apples comparisons between sites and designs. Every score is explainable: users can inspect inputs, weights and assumptions, export reports, and share evidence with stakeholders. With Data Centre Frontier, the Australian government and organisations can choose locations that are faster to permit, cheaper to run, and better for the grid and the environment.

1) We layer trusted public maps over your sketch.
When you draw a site, the tool quietly checks a set of open Australian government datasets available  in the background—electricity lines and substations, internet backbones and cable landings, climate and water, natural hazards, protected areas, population, and planning signals. Think of it like laying tracing paper maps on top of each other to see the full picture.
2) We turn those maps into simple questions.
For each topic, we ask practical, situational questions such as:
•	“How close is reliable high-voltage power?”
•	“Is there decent backhaul internet nearby (on land or via a cable landing)?”
•	“Is the area prone to flood, fire, or earthquakes?”
•	“Is it too hot for efficient cooling, or is water access likely?”
•	“Is the land environmentally sensitive or set aside as protected?”
•	“Are there people and services within a reasonable distance?”
•	“Do planning layers suggest this will be easier or harder to permit?”
3) We score what we find—openly.
Each answer becomes a sub-score (0–100) with clear, human-readable reasons (“5 km to a major substation”, “inside a protected area”, “cooler climate zone”). The overall viability score is just a weighted summary of those sub-scores. You can see the weights and change them to match a smaller edge site, a cloud campus, or an AI-heavy build.
4) We forecast basics using published facts.
Using the same public data (climate normals, typical cooling approaches, power availability signals), the tool gives first-pass estimates of power and water use, operating cost bands, and resilience trade-offs—so different sites can be compared fairly on “apples-to-apples” terms.
5) We show our work.
By telling you where the data for the platform is coming from and having that in a visible area on the platform, you can hold us accountable for mistakes the platform makes, you can independently audit and check if the platform is correct in its assessment, and if not, tell us so we may improve Data Centre Frontier.
6) Keeping Australian Data Sovereignty 
By using Data Centre Frontier, Australia will be able to keep its data domestic out of the hands of foreign countries that may wish us harm while hosting allied and trusted countries' “digital embassies” to further increase our relationship and trust in one another.

Bottom line:
Open data provides the evidence (where power, fibre, hazards, climate and people actually are). Data Centre Frontier converts that evidence into a clear, explainable decision for your specific site—so you know why a location looks strong, what could trip it up, and where to dig deeper before committing.

The Current Prototypes made through the use of ChatGPT-5.0 are proof of concept. One, Tasmania DC Viability uses stub datasets instead of live updating data, but considers more datasets than the second prototype. The second prototype Data Centre Frontier – TAS (Open Data) further proves this concept by using some live data from, GA National Electricity Infrastructure filtered to show transmission lines and substations, DCCEEW CAPAD 2024 (terrestrial) for the protected area, and uses Bom Australia Water Storages to find the reservoir. Both of these Prototypes serves as a proof that our vision is worth investing and looking further into so the full feature rich version of the platform with integration of live data as well as the ability for organizations to import their own data, an AI dedicated to the analysis and consolidation of data to provide greater and more accurate feedback for the end-user can be created and used..
We believe truly for Australia to become the “data centre capital of the Asia-Pacific”, to host “digital embassies”, it will require a platform like Data Centre Frontiers that can make the analysis and selection of sites for future data centres a simple task for both government and companies. 


Within this GitHub
ChatGPT folder contains some saved messages as well as a Word document with the links to the chats.
Data Centre Frontier Briefs contains the Word documents for different versions of the above brief.
Images contain any screenshots or images related to the GovHack 2025 event and project
Tasmania DC Viability Versions contains different versions of a ChatGPT-created web app


