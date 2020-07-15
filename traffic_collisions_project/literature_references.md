# Traffic Collision Literature Review

Links to related projects and papers analyzing traffic collision data. These are examples that might be helpful references.  


## Data Visualization 

#### [New York City Motor Vehicle Collision Data Visualization](https://nycdatascience.com/blog/student-works/new-york-city-motor-vehicle-collision-data-visualization/)  
Hua Yang, posted on Feb 5, 2018, project objectives:  
- Develop an interactive map tool to easily check and explore collision case info on a real city map,  
- Conduct some preliminary exploratory data analysis to get overview results on interested questions.  

The final [Shiny app visualization](https://yanghua23.shinyapps.io/shinyapp_NYC_Motor_Vehicle_Collision) can show a heat map (collision data point intensity), a cluster map (clustered collision data), and lethal collision markers (with detailed collision information pop-up) all at the same time. The user has highly flexible control on what portion of data he/she'd like to see, what year, borough, month range, and for what types of victims (pedestrians, cyclists, motorists) and what severity (no hurt, injured, lethal).  

## Machine Learning

#### [A comparative study on machine learning based algorithms for prediction of motorcycle crash severity](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6448880)  
Lukuman Wahab, Haobin Jiang, Yanyong Guo, Published online 2019 Apr 4. doi: 10.1371/journal.pone.0214966  
In this study, machine learning based algorithms were employed to predict and classify motorcycle crash severity. Machine learning based techniques are non-parametric models without the presumption of relationships between endogenous and exogenous variables. The main aim of this research is to evaluate and compare different approaches to modeling motorcycle crash severity as well as investigating the effect of risk factors on the injury outcomes of motorcycle crashes. Motorcycle crash dataset between 2011 and 2015 was extracted from the National Road Traffic Crash Database at the Building and Road Research Institute (BRRI) in Ghana. The dataset was classified into four injury severity categories: fatal, hospitalized, injured, and damage-only. Three machine learning based models were developed: J48 Decision Tree Classifier, Random Forest (RF) and Instance-Based learning with parameter k (IBk) were employed to model the severity of injury in a motorcycle crash. These machine learning algorithms were validated using 10-fold cross-validation technique. The three machine learning based algorithms were compared with one another and the statistical model: multinomial logit model (MNLM). Also, the relative importance analysis of the attribute was conducted to determine the impact of these attributes on injury severity outcomes.   

#### [Predicting-traffic-accidents-CNN](https://github.com/L-Lewis/Predicting-traffic-accidents-CNN)  
This project considers whether satellite imagery could be combined with other datasets to increase our ability to predict where traffic accidents are likely to occur. Our methodology for this project was to make four models:  
- Model 1 uses a combination of accident, population density and traffic data from the UK, where we focused on accidents in London. Different machine learning models were built to see if the level of accident severity could be predicted.  
- Model 2 uses satellite images of London that were scraped using Google Maps Static API and fed into a Convolutional Neural Network (CNN) in order to predict where traffic accidents are likely to occur.  
- Model 3 then makes use of Keras functional API to combine the top features from model 1 and the image features extracted from a CNN (similar to model 2) to create a mixed-input or mixed data model. Both data types are fed into separate deep learning models and their outputs are combined for the final layers in order to predict whether a given area is likely to have traffic accidents or not.  
- Model 4 uses the same model architecture as model 3, but applies it to the task of distinguishing between areas with no traffic accidents and areas with serious or fatal traffic accidents, in order to predict the locations of the worst traffic accidents.  
