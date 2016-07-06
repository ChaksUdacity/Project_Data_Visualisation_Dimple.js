# Project_Data_Visualisation_Dimple.js
 This project is connected to the final submission for Data Visualisation course using Dimple.js. Data set used: Titanic Data

Data: Titanic Data  - Contains demographics and passenger information from 891 of the 2224 passengers and crew on board the Titanic. Dataset Source: Kaggle website

--------------------------------------------------------------------------------------------------------------------------------------
Summary -
Even though there were less females on board of the Titanic in each class, there were more female survivors of the disaster in each class.

--------------------------------------------------------------------------------------------------------------------------------------
Design Decision explained- 
Intially my design choice was to ensure how many men and women survived travelling in different class , Embarkation port and their age group. I wanted to make it simple so changed to Vertical bar charts.

what was the logic behind the original design?: The original idea was to pack more data into horizontal charts giving readers more info.Once on receiving feedback to the visualization, I understood packing too many parameters is loosing the message. Hence on feedback, I removed age and converted the vertcal bar plot to horizontal bar plot after a nuber of try with horizontal plot bar based on percentile axix (i.e. myChart.addPctAxis("x", "Survived");

why did you end up choosing gender and class when simplifying? : From the data analysis, it was clear that though less females travelled in each class but after the Titanic ship crash, the survival percentage was more for females in each class. Hence naturally, I wanted to bring this insight in a more visually communicating way.


why did you choose a bar chart - why did you think this makes it "simple"? : After experimenting a few, I landed on Bar chart. Bar chart is always elegant and simple since it explains the data more visually.  Audience are also used to viewing bar charts.


why is it a stacked bar chart, why relative sizes instead of absolute ones? Stacked bar chart able to compare the population of different class on equal footing to bring out the percentage of gender in each class. Additionally, Percentage is easy to remember and visualise for the mind than absolute numbers, hence I chose percentage.


why that specific color coding? (Atttention: please read more about the color choice in the "Design" section!): I used natural cool colors instead of strong colors which would put down the audience. Additionally I chose pink for females - the color with which normally females are associated with and blue color for males.

--------------------------------------------------------------------------------------------------------------------------------------

FEEDBACKS:

Feedback II -
Based on the feeedback from Udacity, I limited the number of parameters to three for each charting exercise.  I utilised the no of passengers on board Titanic, the class of passengers travelled and their gender to  produce the first chart. The second set of chart illustrates the passengers survived,  the class of passengers travelled and their gender to cmpare with teh first chart.


Feedback I - include all feedback you received from others on your visualization from the first sketch to the final visualization

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
 
--------------------------------------------------------------------------------------------------------------------------------------

Resources -
list of sources consulted to create visualization : 
(1) Class notes provided at Udacity website 
(2) http://dimplejs.org

--------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------

THE PROCESS OF EDA AND INTERESTING FACTS THAT I STUMBED ON:

Passengers : Of the 891 passengers on board studied, majority of the passengers 577 are male (64.8%) and the rest  314 are female(35.2%) passengers.

Passengers by Passenger_Class: 216 of 891 passengers travelled by 1st class; 184 of 891 passenegers travelled by 2nd Class; 491 of 891 travelled by 3rd class

CHART DATA-I: PASSENGERS ON BOARD TITANIC FOR 1ST, 2ND AND 3RD CLASS BASED ON  GENDER
Passengers by Passenger class and gender: 1st class passenger male passengers 122 (56%) of 216 and female passengers 94 (44%) of 216.
2nd class passengers: male passengers 108 (59%) of 184 and female passengers 76 (41%) of 184. 3rd class passengers: male passengers 347 (73%) of 491 and female passengers 144 (27%) of 491.


Background:
Passengers Survived: Only 342 passengers (38.4%) of the passengers survived. The majority of the survivors are female. 74% of the female passengers (233/314) survived while just 18.8% of male passengers survived(109/577)

Passengers Survived by Gender & Pclass: Survival rate was higher for females travelling by first class (P1) at 96.8% than second class(P2) at 92.1% than third class(P3) at 50.0%


CHART DATA-II: SURVIVED PASSENGERS ON BOARD TITANIC FOR 1ST, 2ND AND 3RD CLASS BASED ON GENDER
Passengers Survived by Passenger class and gender: Survived 1st class passenger  male passengers 45 (33%) of 136 and female passengers 91 (67%) of 136. Survived 2nd class passengers: male passengers 17(20%) of 87 and female passengers 70 (80%) of 87. Survived 3rd class passengers: male passengers 47 (39%) of 119 and female passengers 72 (61%) of 119.




