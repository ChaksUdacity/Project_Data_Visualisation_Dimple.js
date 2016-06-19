# Project_Data_Visualisation_Dimple.js
 This project is connected to the final submission for Data Visualisation course using Dimple.js. Data set used: Titanic Data

Data: Titanic Data  - Contains demographics and passenger information from 891 of the 2224 passengers and crew on board the Titanic. Dataset Source: Kaggle website

Summary -

Passengers : Of the 891 passengers on board studied, majority of the passengers are male (64.8%) and the rest are female(35.2%) passengers.

Survivors: Only 38.4% of the passengers survived. The majority of the survivors are female. 74% of the female passengers (233/314) survived while just 18.8% of male passengers survived(109/577)

Survivor by Age : The chances of survival was higher if the age group is lower

Survivors based on port of Embarkment: Survival were higher for Embarkment at Cherbourg(55%) than Queenstown(38.9%) and Southampton(33.7%)

Survivors by Gender & Pclass: Survival rate was higher for females travelling by first class (P1) at 96.8% than second class(P2) at 92.1% than third class(P3) at 50.0%



Design - 
Intially my design choice was to ensure how many men and women survived travelling in different class , Embarkation port and their age group. I wanted to make it simple so chose Vertical bar charts

Once on receiving feedback to the visualization, I understood packing too many parameters is loosing the message. Hence on feedback, I removed age and converted the vertcla bar plot to horizontal bar plot after a nuber of try with horizontal plot bar based on percentile axix (i.e. myChart.addPctAxis("x", "Survived");



Feedback - include all feedback you received from others on your visualization from the first sketch to the final visualization

Person (1) Kristien Ahlgren as below:

What do you notice in the visualization?: 
  The main message from the whole thing is, if you were rich and female, you had much better changes...they loaded the money folks to lifeboats first, ladys first.. The places where rich folks came fall into that category
  
What questions do you have about the data?: 
  Data is reasonable
  
What relationships do you notice? : 
 Rich and being women stands a better chance of survival
 
What do you think is the main takeaway from this visualization?: 
 Survival chance is good for weaker sex
 
Is there something you don’t understand in the graphic : 
 Visualisation : The chart is not good, how to interpret the age is odd..e.g. Why show combined age..


Person (2) Eleaiya Bharati as below:

What do you notice in the visualization?:
   For this problem , you need to use different charts. May be a bar chart with survival and  few questions to plot
   
What questions do you have about the data?: 
I still feel too many parameters and incomplete data set on graph.I feel bar chart not good.
What relationships do you notice?: 
 
What do you think is the main takeaway from this visualization?: 
Needs clarity

Is there something you don’t understand in the graphic:
too many parameters plotted

Person (3) Harish lagu as below:

What do you notice in the visualization?: 
  Its good to be a woman, chances of survival are good.
  
What questions do you have about the data? :
 data is ok. 
 
What relationships do you notice?: 
 Probably you will have to be rich and old to survive?
 
What do you think is the main takeaway from this visualization?: 
 There was a concious decision on the ship by captain and  people on board since the life boats are limited.
 
What do you notice in the visualization? :
 Looks like a simple age vs class chart, I dont fully understand
 

Person (4); Varun Narayanan (student) as below:

What do you notice in the visualization?: :
  Women are laways alert to get out. May be the people sitting close to the door escaped first



Resources -
list of sources consulted to create visualization : 
(1) Class notes provided at Udacity website 
(2) http://dimplejs.org
