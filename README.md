# Analyzed-Motor-Vehicle-Collisions

In analyzing the Motor Vehicle Collisions - Crashes dataset, I utilized Python and Meteostat for advanced data analysis. Python facilitated data processing, exploratory data analysis, and statistical computations, while Meteostat provided weather data integration to assess its influence on collision patterns and contributing factors. This approach enabled a comprehensive evaluation of trends and insights to inform strategies for enhancing urban safety and mitigating collision risks.

## Table of Contents

1. - [Project Overview](#project-overview)
2. - [Dataset Description](#dataset-description)
3. - [Key Findings](#key-findings)
4. - [Collision Trends by Borough](#collision-trends-by-borough)
5. - [Top Contributing Factors to Collisions](#top-contributing-factors-to-collisions)
6. - [Vehicle Injury Types Across Seasons](#vehicle-injury-types-across-seasons)
7. - [Pedestrian, Cyclist, and Motorist Injuries by Borough](#pedestrian-cyclist-and-motorist-injuries-by-borough)
8. - [Most Deaths by Vehicle Type](#most-deaths-by-vehicle-type)
9. - [Conclusion](#conclusion)
10. - [Recommendations](#recommendations)
11. - [References](#references)


## Project Overview
I analyzed the Motor Vehicle Collisions - Crashes dataset from NYC Open Data. This dataset contains details of all motor vehicle collisions reported by the NYPD in the Bronx, Brooklyn, Queens, Manhattan, and Staten Island. I focused on data from 2019 to 2022 to identify trends and outliers, as this period includes pre-COVID, during-COVID, and post-COVID data. With 26 different columns in the dataset, I selected specific identifiers to support my analysis. These identifiers include:

1. Total collisions per borough per year.
2. Top collision contributing factors.
3. Vehicle injury type per borough, per time of day, & per season.
4. Number of people killed by vehicle type.
5. Weather as a contributing factor to motor vehicle collisions.

## Dataset Description:
The dataset was released by the New York City government and provides invaluable insights into motor vehicle collisions in NYC, serving as a crucial resource for analyzing trends and patterns in these incidents. I selected this dataset because motor vehicle collisions pose significant public safety concerns and carry substantial economic and social costs. 
My objective is to leverage these findings to provide policymakers with informed insights and contribute to the development of robust strategies aimed at mitigating both the 
frequency and severity of these collisions.

## Key Findings:

#### Collision Trends by Borough:
- Brooklyn experiences the highest number of motor vehicle collisions each year, ranging from 70,405 to 70,518.
- Staten Island experiences the lowest number of motor vehicle collisions each year, ranging from 8,717 to 8,731.

<img width="648" alt="Screenshot 2024-06-30 at 2 23 29 PM" src="https://github.com/YamouJ/Analyzed-Motor-Vehicle-Collisions/assets/167350506/fc0ca5c4-b354-4334-9543-dbb86ae27322">


#### Top Contributing Factors to Collisions:
- Inattentive or distracted driving.
- Failure to yield the right of way.

<img width="648" alt="Screenshot 2024-06-30 at 2 09 30 PM" src="https://github.com/YamouJ/Analyzed-Motor-Vehicle-Collisions/assets/167350506/2e128360-7fef-47d9-975b-711631b70b56">


#### Vehicle Injury Types Across Seasons:
- Fall Season: The highest number of pedestrian injuries occurs during this time of year.
- Summer: The highest number of motorist and cyclist injuries occurs during this time of year.

<img width="566" alt="Screenshot 2024-06-30 at 2 30 48 PM" src="https://github.com/YamouJ/Analyzed-Motor-Vehicle-Collisions/assets/167350506/d229d799-2ea7-4792-9745-f6234604cb70">
<img width="566" alt="Screenshot 2024-06-30 at 2 30 10 PM" src="https://github.com/YamouJ/Analyzed-Motor-Vehicle-Collisions/assets/167350506/56bcf2d2-cd59-4943-be68-45d26129d786">


#### Pedestrian, Cyclist, and Motorist Injuries by Borough:
- Brooklyn has the highest number of accidents and injuries in all categories.
- Most collisions occur between 12 PM and 6 PM.

<img width="566" alt="Screenshot 2024-06-30 at 2 38 05 PM" src="https://github.com/YamouJ/Analyzed-Motor-Vehicle-Collisions/assets/167350506/c3fd1c90-2834-4efc-9e17-56bb4b87884b">
<img width="566" alt="Screenshot 2024-06-30 at 2 34 58 PM" src="https://github.com/YamouJ/Analyzed-Motor-Vehicle-Collisions/assets/167350506/072ca039-711d-4068-af80-bd7b0cc3daba">


#### Most Deaths by Vehicle Type:
- Sedan
- Station Wagon/Sport Utility Vehicle

<img width="900" alt="Screenshot 2024-06-30 at 2 26 39 PM" src="https://github.com/YamouJ/Analyzed-Motor-Vehicle-Collisions/assets/167350506/dd59978e-4821-44d3-a24b-fc926d86b9ca">


## Conclusion

Analyzing the Motor Vehicle Collisions - Crashes dataset from NYC Open Data has provided critical insights into the dynamics of motor vehicle collisions across New York City. The data underscores the pronounced impact of collisions on public safety, economy, and social well-being. Brooklyn emerges as a focal point with the highest collision rates annually, contrasting sharply with Staten Island, which records the fewest incidents.

The identified top contributing factors—namely, inattentive or distracted driving and failure to yield the right of way—highlight areas where targeted interventions could yield significant safety improvements. Moreover, seasonal variations in injury types underscore the need for context-specific strategies, such as focusing on pedestrian safety in the fall and addressing motorist and cyclist safety during summer months.

This analysis not only enhances our understanding of collision trends but also underscores the imperative of data-driven decision-making in shaping effective public policy and enhancing urban safety.

## Recommendations

To address the challenges highlighted by this analysis, policymakers should leverage these insights to develop proactive measures aimed at reducing both the frequency and severity of motor vehicle collisions in New York City. Evidence-based interventions should prioritize addressing the identified top contributing factors, with targeted campaigns and enforcement efforts aimed at reducing inattentive or distracted driving and improving right-of-way compliance. Additionally, implementing seasonal safety initiatives can mitigate risks during high-incidence periods for pedestrians, cyclists, and motorists. By fostering collaboration between governmental agencies, community organizations, and the public, New York City can work towards a safer and more resilient transportation environment.

### References 
- Meteostat weather API
- ChatGPT





