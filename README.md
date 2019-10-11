# Predict apartment price in Victoria using Regression
### created by Putri Bunga Rahmalita
------------------------------------------------------------------
In this program I want to help Tony to predict apartment price in Victoria. Tony who has profession as a broker wants to predict apartment price in Victoria based on living area environment and apartment conservation status. Determine the best model to predict and redefine new conservation variable in 3 level : 
A = 1A,<br>
B = 2A, <br>
C = 2B and 3A. <br><br>

The Dataset provides living area and conservation status. There are 218 observations and 16 variables. The columns in this dataset are :
  - row.labels : row of the data
  - totalprice : price of the apartment in Victoria
  - area : area apartment unit 
  - zone : zone where the apartment unit is located
  - category : category of apartment unit 
  - age : age of the apartment unit from the time it was first built
  - floor : the floor where the apartment unit is located
  - rooms : rooms contained in the apartment unit
  - out : the closest exit to the apartment unit
  - conservation : conservation (group/categoric) of apartment unit
  - toilets : bathroom contained in the apartment unit (2 = 2 toilets, 1 = 1 toilet, 0 = none)
  - garage : garage contained in the apartment unit (2 = 2 garage, 1 = 1 garage, 0 = none)
  - elevator : whether or not there is an elevator in the apartment unit (1 = available, 0 = none)
  - streetcategory : street category where the apartment unit is located
  - heating : the hot air zone in the apartment unit
  - tras : availability of available bins (1 = available, 0 = none)
<br><br>
I used linear regression for forecasting or prediction analysis that is often used on quantitative scale data (intervals or ratios). Regression Linear used to determine the effect of one or several variables on one variable. Variables that influence are often called independent variables, independent variables or explanatory variables.
<br>
First, I clean the dataset using REGEX and then I explore the data to know what the meaning and insight from the data. I used data visualization with different plot (ex : bar plot, line plot, etc) to understand the importance of context and content. Data visualizatino included univariate and bivariate analysis to know analysis carried out for one variable and analysis that uses two features to find out the relationship contained in the two features.
<br>
<br>
Next, I do variable selection to choose the variable for modelling with linear regression. I choose area, floor, rooms, toilets, garage, elevator, tras, and conservation because based on correlation between these data have a large or mutually influential relationship. Then, I predict totalprice data to know based on the criteria of the features that I have chosen, what is the appropriate price for an apartment unit using linear regression. After that, I count the error from that model to represents error between the prediction results with the actual value.
<br>
<br>
For more details, please open my code, and if there are questions feel free to ask me :)
