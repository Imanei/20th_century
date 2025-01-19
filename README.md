# 20th Century Geopolitical Analysis
## Data Visualization with Python: Building a Historical Network Analysis:

## Objective
The Institute for Public Policy needs an analytical overview and visualization of the interrelations between countries throughout the twentieth century. Given the volatility of world politics, the Institute is looking for historical ties between different countries to inform its research.

This project aims to:
- Identify key countries and their roles in shaping 20th-century geopolitical events.
- Analyze historical relationships using centrality measures (degree, closeness, betweenness).
- Visualize country interconnections and communities using advanced graph analysis techniques.

---

## Project Overview
This repository provides a comprehensive analysis of the interrelations between countries in the twentieth century. It includes:

1. **Data Processing**
   - Historical data of geopolitical events and relations were compiled and transformed into a network graph, where:
     - Nodes represent countries.
     - Edges represent significant historical ties or interactions.

2. **DATA SOURCE**
   -Data was scraped from the Wikipedia page, [Key events of the 20th century](https://en.wikipedia.org/wiki/Key_events_of_the_20th_century).
   Using `BeautifulSoup` the full text of the article was saved as a text file, `20th Century Events.txt`.
   And using `Selenium`, all names of countries in the article were compiled into a csv file `countries_list_20th_century_1.5.csv`.

3. **Graph Analysis**
   - Using `NetworkX`, the network was analyzed for:
     - **Degree Centrality**: To determine countries with the highest direct connections.
     - **Closeness Centrality**: To identify central countries capable of quickly reaching others in the network.
     - **Leiden Communities**: To detect clusters of countries with shared historical or geopolitical ties.

4. **Visualizations**
   - **Network Graph**: A visual representation of the country relationships, color-coded by communities identified via the Leiden algorithm.
   - **Centrality Plots**: Bar charts showcasing the countries with the highest degree and closeness centrality scores.
---

## Requirements
To run the project, the following libraries are required:
- `Python==3.10`
+ [Requirements files](https://github.com/Imanei/20th_century/tree/main/Requirements)

---

## Conclusion
This project provides valuable insights into the historical interrelations of countries in the 20th century. By understanding the roles and connections of different nations, researchers can better inform their geopolitical analyses and policy recommendations. The visualizations and metrics offer a clear and impactful way to grasp the complexities of world politics during this turbulent period.
[Final report](https://github.com/Imanei/20th_century/blob/main/Task%207.md)

