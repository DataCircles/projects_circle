# Traffic Collisions Project

This six week project analyzes the Seattle area traffic collision data collected by the Seattle Dept. of Transportation (SDOT) over the years, 2004 - 2020.  

## About the final presentations

The virtual presentations will be during the week of Sept. 14, vote in the Slack poll to determine the day.  

The presentations are open to the public, feel free to invite any colleagues, friends, or family.  

The presentations will be approximately 15 minutes long with 5 minutes for questions.  

See Slack for additional information.  

## About the final product

This [example github repository](https://github.com/jfear/example_project) illustrates one way to organize your repository.  

At a minimum, each team repository should have a readme page that describes:
- the team members,
- the questions or issues the team focused on,  
- the intended audience, 
- the data (where the data came from, what it looked like, and links to data source), and 
- the project process.  

The readme page should also have links to any final presentation slides or visualization pages.  

## About the project

This repository contains general project documentation, [workshop materials](https://github.com/DataCircles/projects_circle/tree/master/traffic_collisions_project/workshop_materials), and other resources for the teams working on the Traffic Collisions Project. The teams focus on different business questions and will deliver different data science products. Each team falls under one of two tracks:  

__1. Data Visualization Emphasis Track__  
Input: geolocation data on collisions, road conditions, weather conditions  
Output 1: Generate maps with geopandas, folium, pandas  
Output 2: Generate dashboard with Tableau, Google data studio  

__2. Machine Learning Emphasis Track__  
Input: geolocation data on collisions, road conditions, weather conditions  
Output 1. Classify and label collisions based on degree of danger, decide how to classify what constitutes a dangerous or not dangerous intersection  
Output 2. Predict the danger level of each intersection  
Output 3. Recommend changes to improve dangerous intersections based on similarity metrics  

#### Project teams:  

__[Data Visualization Team Repository](https://github.com/DataCircles/traffic_collisions_viz_team)__  

__[Machine Learning Team 1 Repository](https://github.com/DataCircles/traffic_collisions_ml_team1)__  

__[Machine Learning Team 2 Repository](https://github.com/DataCircles/traffic_collisions_ml_team2)__  

__[Machine Learning Team 3 Repository](https://github.com/DataCircles/traffic_collisions_ml_team3)__  

### Proposed project goals

- Identify dangerous locations 
- Identify predictors of traffic collisions, e.g., physical characteristics of the location, road condition, DUI, weather
- Examine increase or decrease in number of collisions over time
- Identify predictors of increases or decreases in the rate of collisions
- Recommend improvements to dangerous locations  
 
### Initial Datasets

- __Traffic Collision Data__ from the Seattle Transportation Dept. (SDOT), see the [data description](https://data-seattlecitygis.opendata.arcgis.com/datasets/collisions) ([csv data](https://opendata.arcgis.com/datasets/5b5c745e0f1f48e7a53acec63a0022ab_0.csv))  
- __Seattle Street Data__ from the SDOT, see the [data description](https://data-seattlecitygis.opendata.arcgis.com/datasets/seattle-streets?geometry=-123.455%2C47.447%2C-121.200%2C47.771) ([csv data](https://opendata.arcgis.com/datasets/383027d103f042499693da22d72d10e3_0.csv))  
- __Neighborhood Census Data__ from the American Community Survey, 5-year Series 2013-2017, the data was aggregated by neighborhood (aka Community Reporting Area boundaries) see the [data description](http://data-seattlecitygis.opendata.arcgis.com/datasets/00f231c5a5084d079fcbf7ba9ad2e37e_0) ([csv data and spatial files](https://data.seattle.gov/Land-Base/A-Community-Reporting-Areas-Profile-ACS-5-year-201/8x5n-chs7))  

## Initial Project Tasks and Milestones

### Week 0 (aka week of Project Kickoff)  
#### Tasks
1. Introduce yourselves to your teammates  
2. Document the business problem(s) and scope of the project  
3. Decide team logistics:  
a. how to communicate, e.g. email, Slack  
b. how to track team progress, e.g. Trello, GitHub Project Board, Google Doc  
c. how to work collaboratively, e.g. GitHub repository, Google Drive  
d. how to divide up the work, e.g. assign team roles, work independently then compare  
#### Milestone(s)
1. Deliver the project charter to document the business problem and scope of the project. Report can be in any format (_e.g._ Markdown, Google doc, Jupyter notebook), but it should be in each team's repository by 6 p.m. on Wednesday, July 15th.  
2. Select a team representative to deliver a team progress report at standup meeting  

### Week 1 
#### Tasks
1. Produce a Jupyter notebook with a data report to document:  
a. the structure and statistics of the raw data  
b. how the data can help answer the business problem(s)  
c. what additional data is needed to answer the business problem(s)  
2. Locate the additional data  
2. Focus on honing your "business understanding," essentially what the problem is and who your audience is.  
3. Decide on the final key questions you want to answer.  
#### Milestone(s)
1. Deliver the data report. The data report should be in each team's repository by 6 p.m. on Thursday, July 23.  
2. Select a team representative to deliver a team progress report at the Thursday standup meeting. Note, please choose a new person each week so everyone has a chance to present.  

### Week 2
#### Tasks
1. Decide as a team what are the most important tasks. Perhaps, it's cleaning and formatting the dataset or producing an exploratory data analysis report.  
2. Discuss what the essential tasks are to complete a minimum viable result, versus the goal or ideal results. The goal is to efficiently make progress on the essential tasks.    
#### Milestone(s)
1. Describe the project's minimum viable result and the goal result.  
2. Select a team representative to deliver a team progress report at the standup meeting. Note, please choose a new person each week so everyone has a chance to present.  

__Check your team's Slack channel for additional goals and deadlines.__  

## Best practices for organizing data science projects

1. Use the same structure and names across projects
2. Separate original data, generated data, and scripts
3. Use workflows to orchestrate
4. Split out configuration for consistency
5. Modularize reusable code
6. Use a style guide and linters
7. Use containers and environments
8. Document as you go: note how to do particular tasks, note the decisions that you make and why, and _etc._  

List from [organizing_data_science_projects](https://cbiit.github.io/p2p-datasci/2019-12-12-organizing_data_science_projects/)  
