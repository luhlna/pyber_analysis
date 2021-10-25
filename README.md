# pyber_analysis

## Overview 
PyBer is a Python based ride-sharing app, who wants an exploratory analysis to showcase the relationship between the type of city and the number of riders and drivers.

## Results
With two datasets with the information of three city types, amount of drivers and the detais of each ride we performed an analysis to determine relationships between the data.

At first we merged both datasets by the city name, just to gather the information in one dataframe:
<img width="619" alt="Screen Shot 2021-10-25 at 2 19 11" src="https://user-images.githubusercontent.com/90527212/138651429-8077ce6c-c837-4a01-93b5-d561b83a7d15.png">

Then we started the analysis by organizing the data by type of city, to get an overview of it's behaviour.
<img width="619" src=https://github.com/luhlna/pyber_analysis/blob/d4434fe2d71c2fd6b1cac21dec7f7f56d17b3096/analysis/Fig1.png>

We found that an indirect relationship between the number of riders and drivers in each city type and the fares; frist a direct relationship between rides and drivers, where the number of drivers is proportional to the number of riders in each type of city.

In the case of rural cities there are about 3.5 and 2.5 times less riders than urban and suburban cities:
<img width="619" src=https://github.com/luhlna/pyber_analysis/blob/d4434fe2d71c2fd6b1cac21dec7f7f56d17b3096/analysis/Fig2.png>

Which then translate on having from nine to four times less drivers than in urban and suburban cities:
<img width="619" src=https://github.com/luhlna/pyber_analysis/blob/d4434fe2d71c2fd6b1cac21dec7f7f56d17b3096/analysis/Fig4.png>

And even if the rural cities just represent 6.8% of the total fares, the average fare per Ride is about $34.62 per Ride, that's $10 above the Urban cities fare.
<img width="619" src=https://github.com/luhlna/pyber_analysis/blob/d4434fe2d71c2fd6b1cac21dec7f7f56d17b3096/analysis/Fig5.png>

Therefore there is a indirect relation with the average fare of each type of city.

## Summary
Thanks to the analysis we identified the relationships between the number of rides and drivers to the fares.

<img width="619" src=https://github.com/luhlna/pyber_analysis/blob/d4434fe2d71c2fd6b1cac21dec7f7f56d17b3096/analysis/Fig3.png>

We reccomend PyBer to closely monitor the fares by city types; because in the case of rural areas this might also be affecting the number of riders due to high prices. In the case of suburban and urban cities we reccomend launching a marketing campaign or invest in attracting more customers, because the number of drivers is too high in comparision to the riders. 
