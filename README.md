# Nigeria-Poverty-Unemployment-Analysis
INTRODUCTION; Nigeria is an African Country known for its  multi-ethnic and culturally diverse nature.Despite having the largest population and economy in Africa, the Country offers limited oppurtunities to most of its citizens.The poverty rate is estimatd to have reached 38.9% in 2023, with an estimated 87 million Nigerians living below poverty line .Nigeria is believed to be the world's second largest poor population after india. The unemployment rate in Nigeria is said to have increased to 5% in the 3rd quarter of 2023 from 4.20% in the 2nd quarter.

OBJECTIVE; The purpose of this analysis is to know the relationship between poverty and unemployment and how it affects the people of Nigeria across the 36 states of the federation from the period of 2019 to 2020. 

DATA COLLECTION; Three different dataset was used for this analysis, they are 1. Unemployment rate by state 2. Poverty headcount rate in Nigeria and the 3. Geopolitical zones of Nigeria. The first two was gotten Statista while the third one was from wikipedia.

DATA CLEANING; PowerBi was used for data cleaning, the data was loaded and moved to power querry editor. Some  of the Columns was renamed and header promoted, dropped some columns that is not relevant to the analysis. After perusing the tables, I changed the data type accordingly,Splited some columns to remove irrelevant texts.To split column; go to Home-Split column-split column by-delimiter this delimiter coild be a comma sign or space -left most delimiter. I was also able to Transpose geopolitical zone table to seperate states from geopolitical zone. This was done by Clicking on the shift key- Transform-Unpivot. To Unipivot Columns Tap on all the states Column-hold shift key-tap the all states column then remove attributes key.

DATA MODELLING; Using powerbi, i was able to model the three (3) tables together i.e merging the unmeployment , poverty and geopolitical states  datasets.They all have one to one (1-1) relationship.
After cleaning and modelling the 3 datasets, I moved the datasets from power querry editor  to PowerBi desktop by using the close and apply button.

ANALYTICAL METHODS; Created new measure on 2019 poverty rate and 2020 unemployment rate. Dashboard was also created to visualize findinds.

INSIGHTS; the pdf folder contains the dashboard.

OBSERVATION ; In 2019, the total sum of poverty rate across the 36 states in Nigeria including FCT is 1524.76%. The North West region accounted for (453.95%)
29.77% which is the highest poverty rate in the six geopolitical zones of the country. This could be as a result of the insecurity in the region , many
people have been displaced from their homes and they have lost their source of livelihood. Using funnel chart to check for the top 10 states with
highest poverty rate, Sokoto state tops the rank with 87.73% and Osun state ranked the lowest with 8.50%.
Using the Area chart to visualize 2020 unemployment rate by geopolitical rate, at 263.08%, South South region had the highest Sum of
unemployment rate in 2020 and was 98.64% higher than South West, which had the lowest Sum of unemployment in 2020 at 132.44%. South South
accounted for 21.10% of Sum of unemployment 2020. Across all 6 Geopolitical zone ,the Sum of unemployment rate 2020 ranged from 132.44% to
263.08%.
From the analysis, it was observed that South west region had the lowest Poverty rate in 2019 and the lowest Unemployment rate in 2020 this could be
as a result of 
Across the 36 states, top 10 states with the highest sum of Unemployement rate is Yobe State accounted for the highest poverty rate with 21.65% sum
of poverty and Osun state ranked the lowest with 11.65%.

RECOMMENDATIONS; The federal government should seek the help of experts on  how to resolve insecurity issues in the country especially the northwest region of the country.Security agents should be well trrained and equiped with weapons and protective equipment, also drones shoud be used to monitor high risk areas.When these are done properly it may reduce the issue of insecurity and by so doing normalcy will return and natives would be able to go back to their abandoned farm and continue their normal buisness thereby  reducing poverty to an extent.

Government should invest in education and provide job opportunities for youth this may help reduce insecurity by providing alternatives to crime.Theres a saying that says 'An ideal mind is the deveils workshop'. When they are busy working and earning legitimataly, Crime will be the last thing on their minds.

In the south west region of the country (Kwara state,Ondo state,Osun state,Ekiti state,Oyo state and lagos state).More industries should be built in that region so that qualified candiddates can be employed by so doing  reducing unemployment rate.

DATASET REFERENCE; https://www.statista.com/statistics/1119533/unemployment-rate-in-nigeria-by-state/
https://www.statista.com/statistics/1121438/poverty-headcount-rate-in-nigeria-by-state/
https://en.wikipedia.org/wiki/Geopolitical_zones_of_Nigeria
