
# Analyzing Urban Homicide Data

The Washington Post collected data on more than 52,000 criminal homicides over the past decade in 50 of the largest American cities.

The data included the location of the killing, whether an arrest was made and, in most cases, basic demographic information about each victim

> [!NOTE]
>  It is important to clarify that the results and conclusions presented here should be used solely for academic or research purposes.


# EDA

## Distribution of Victim Ages

![Distribution of Victim Ages](https://github.com/alexxcode/Analyzing-Urban-Homicide-Data/blob/main/images/ages.png)

**Insights:**

- Right-skewed distribution: The age distribution is skewed to the right, indicating that most victims are relatively young, with a significant concentration in the 20-40 age range.

- Peak in middle adulthood: There's a pronounced peak around the age of 30, suggesting this age group is most vulnerable to homicide.

- Gradual decline after 40: The frequency of victims decreases gradually with increasing age. However, there's a notable number of victims older than 60.

- Few cases at age extremes: There are very few cases at the youngest and oldest age extremes (0-20 and 80-100), which could indicate these age groups are less likely to be homicide victims or that the data for these groups is less complete


## Homicide Over Time (per year)

![Homicide Over Time (per year)](https://github.com/alexxcode/Analyzing-Urban-Homicide-Data/blob/main/images/overyears.png)

**Insights:**

- Initial Increase: The graph shows an initial increase in homicides from 2007 to 2016. This suggests a period of rising violent crime rates.

- Peak in 2016: The highest point of the graph is reached in 2016, indicating the peak year for homicides during the timeframe analyzed.

- Slight Decrease: After 2016, there's a slight decrease in homicides, suggesting a potential turning point or stabilization in the crime rate.

- Years with Notable Increases: The years 2010, 2012, and 2016 stand out with particularly high numbers of homicides.

- Years with Notable Decreases: While the overall trend is upward, there are years (e.g., 2008, 2009, and 2014) where the number of homicides decreased compared to the previous year.

## Homicide Over Time (per month)

![Homicide Over Time (per month)](https://github.com/alexxcode/Analyzing-Urban-Homicide-Data/blob/main/images/overmonths.png)

**Insights:**

- Seasonal Fluctuations: The graph reveals distinct seasonal patterns in homicide rates.

- Peak in July: The highest number of homicides occurs in July, followed by a general decline in subsequent months.

- Lowest Point in February: The month of February consistently shows the lowest number of homicides.

- Summer Months: June, July, and August typically experience higher homicide rates.

- Winter Months: December, January, and February generally have lower homicide rates.

- Month-to-Month Variations: There can be significant fluctuations in homicide rates from one month to the next, even within the same season.

## Distribution of homicide by Race

![Distribution of homicide by Race](https://github.com/alexxcode/Analyzing-Urban-Homicide-Data/blob/main/images/byrace.png)

**Insights:**

- Disproportionate Impact on Black Individuals: The graph clearly indicates that Black individuals are disproportionately affected by homicides, with a significantly higher count compared to other racial groups.

- Lower Rates for Other Groups: Hispanic, White, Asian, and "Other" individuals experience substantially lower homicide rates than Black individuals.


## Distribution of Victim Sex

![Distribution of Victim Sex](https://github.com/alexxcode/Analyzing-Urban-Homicide-Data/blob/main/images/bysex.png)

**Insights:**

- Disproportionate Impact on Males: The graph clearly indicates that males are disproportionately affected by homicides, with a significantly higher count compared to females.


## Distribution of Victim disposition

![Distribution of Victim disposition](https://github.com/alexxcode/Analyzing-Urban-Homicide-Data/blob/main/images/disposition.png)

**Insights:**


- "Closed by Arrest" as the Largest Category: The "Closed by Arrest" bar is taller than the other two, by a small margin, but underscores its dominance in the distribution.

- "Open/No Arrest" as the Second Largest Category: "Open/No arrest" cases represent a substantial portion of the total cases, indicating a significant number of homicides remain unsolved, highlighting a pressing issue in the criminal justice system.

- Smaller Proportions for "Closed without arrest": "Closed without arrest" cases represent a relatively small percentage of the total cases.


## Top 10 Cities with the Most Homicides

![Top 10 Cities with the Most Homicides](https://github.com/alexxcode/Analyzing-Urban-Homicide-Data/blob/main/images/cities.png)

**Insights:**

- Chicago Dominates: Chicago stands out as having the highest number of homicides by a significant margin, exceeding the next city by over 1,000 cases.

- Midwestern Cities Prevail: The majority of the cities in the top 10 are located in the Midwest, particularly the Great Lakes region. This suggests that factors unique to this region, such as socioeconomic disparities, gang violence, or gun access, may contribute to higher homicide rates.

- Southern Cities Also Represented: Several Southern cities, including Houston, Baltimore, and New Orleans, are also included in the top 10. This suggests that regional factors, such as poverty, drug-related crime, or historical tensions, may play a role in these areas.

- Los Angeles and Detroit: While not at the top of the list, Los Angeles and Detroit, both major metropolitan areas, still rank among the cities with the highest homicide rates. This indicates that large cities, regardless of region, may face unique challenges related to crime and violence.



# Comprehensive Analysis of Homicide Data

- **Age Distribution:** The majority of homicide victims are young adults (20-40 years old), with a peak around the age of 30.

- **Temporal Trends:** Homicide rates have fluctuated over time, with an initial increase followed by a slight decrease. There are also distinct seasonal patterns, with higher rates in summer months and lower rates in winter.

- **Racial Disparities:** Black individuals are disproportionately affected by homicides, with significantly higher rates compared to other racial groups.

- **Gender Disparities:** Males are more likely to be victims of homicide than females.

**Case Resolution:** A significant portion of homicide cases are closed through arrests, but a substantial number remain unsolved.


# Notebook: 
(https://github.com/alexxcode/Analyzing-Urban-Homicide-Data/blob/main/eda.ipynb)

