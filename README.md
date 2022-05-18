# SpaceX Falcon 9 First Stage Landing Prediction
This repository houses my applied data science capstone project for the IBM Data Science Professional Certificate.
## Objective
Predict if the Falcon 9 first stage will land successfully.
## Background Information
SpaceX advertises Falcon 9 rocket launches on its website with a cost of $62 million. Other non-SpaceX options can cost upward of $165 million. A large factor in the savings with SpaceX is because the first stage of the rocket can land and be reused. If we can predict if the first stage will land successfully, we can predict the cost of a launch. For a competing company, this is key information that could be the difference between winning or losing a bid against SpaceX. 
## Methodologies
Part 1: Collecting data from the SpaceX API and organizing it in a pandas dataframe

Part 2: Web scraping launch records from Wilipedia using BeautifulSoup and organizing the information in a pandas dataframe

Part 3: Data wrangling to identify landing success/failure for each launch and determine the landing success rate

Part 4: Exploratory data analysis with SQL to understand the dataset and gather insights

Part 5: Exploratory data analysis with visualization using Matplotlib and Seaborn

Part 6: Data visualization with Folium to gain insights on geopgraphic conditions

Part 7: Further data analysis with the use of a dashboard application built on Dash and Plotly

Part 8: Predicting landing outcomes with machine learning techniques (Logistic Regression, Support Vector Machine, Decision Tree, and K-Nearest Neighbors)
## Insights
*  The overall landning success rate was 72%
*  The landing success rate has generally increased over time
![alt text](https://github.com/edwardjmoore/SpaceX-Falcon-9-First-Stage-Landing-Prediction/blob/main/images/successrate.png?raw=true)
*  The first stage is more likely to land successfully as the number of completed flights increases
![alt text](https://github.com/edwardjmoore/SpaceX-Falcon-9-First-Stage-Landing-Prediction/blob/main/images/payloadmass-vs-flightnumber.png?raw=true)
*  Launch site CCFS has a lower landing success rate than the other launch sites
![alt text](https://github.com/edwardjmoore/SpaceX-Falcon-9-First-Stage-Landing-Prediction/blob/main/images/launchsite-vs-flightnumber.png?raw=true)
*  Flights with GTO orbit are less likely to land
![alt text](https://github.com/edwardjmoore/SpaceX-Falcon-9-First-Stage-Landing-Prediction/blob/main/images/orbit-vs-flightnumber.png?raw=true)
