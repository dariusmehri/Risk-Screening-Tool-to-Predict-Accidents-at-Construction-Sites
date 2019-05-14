A Python program was developed to automatically identify high risk construction sites. The criteria determing whether a building is high risk, more likely to have an accident, was based on on a logistic regression model where the outcome variable was an accident at the building in 2017. Independent variables included building characteristics, number of permits active at the site, type of building permit and buildings with accidents prior to 2017.

Based on the results of the model, rules were incorporate in the risk tool. Buildings with active permits were ranked from 1 to 8 on the following risk factors:

Number of permits: 1-4 permits = 1, 5-7 = 2, 8-10 = 3, 11+ = 4

Buildings with a new building: Yes = 1, No = 0

Buildings with a shed, scaffold or fence permits: Yes = 1, No = 0

Buildings with 10+ floors: Yes = 1, No = 0

Buildings with accidents pior to 2017: Yes = 1, No = 0

The Python program is run daily and it automatically calculates the risk for each building and results are presented in a D3 spatial map.



![risk_screening_pic](https://user-images.githubusercontent.com/11237613/42952541-b0a33ef2-8b46-11e8-89cb-9ea7a3330a8a.png)
