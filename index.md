# COVID-19 AND WORLD NATIONS' DIET PLANS

## OBJECTIVE

The project is intended to find the suitable diet pattern that helps to minimize the chances of getting the covid disease. 

## EXPLORING DATASET
The dataset for the project was downloaded from the Kaggle(include the HTTP link here) website. The dataset records all the importand diet components or food variables of a counrtry along with its corresponding covid related information such as 'recovered', 'deaths', 'active' and 'total population'. The dataset records the value of diet variables as percentage intake of that particular food item. For example if a value corresponds to 'Animal Fats' says 0.19, it means that the proportion of animal fat in the food consumed by that country is 19%. The dataset records the values for 170 countries. The data regarding the covid was collected from the Johns Hopkins Center for Systems Science and Engineering CSSE website.
Additionaly, the dataset also records the values of undernourishment rates and obesity rates of each of the countries in the dataset.

## DATA-PREPROCESSING
The dataset recorded the values of total confirmed cases, recovered cases, active cases and total deaths as percentage of the total population. In order to make meaningful statistical analysis the variables need to be converted to the real number format, which was done by multiplying the values with the corresponding population data. Moreover, the dataset also contained inconsistent data points which got removed by eliminating those rows that contained those points. 

## EXPLORATORY DATA ANALYSIS
### Country vs. Obesity Rate

![Picture7](https://user-images.githubusercontent.com/25582927/145690043-9701ccd4-ae1c-4da9-a301-e892940ea86c.png)

The above horizontal bar plot visualization helps to understand the obesity rates of the various countries. The country with the highest obesity rate is USA while the country with the lowest obesity rate is Vietnam.

### Country vs. Undernourished Rate

![Picture8](https://user-images.githubusercontent.com/25582927/145690389-be1f5d54-77a2-4137-b3f9-f271bad9375a.png)

From the graph it can be clearly understood that the country with the most undernourishment rate is Zimbabwe followed by Zambia and Yemen. While, countries like USA, UK, Sweden, Switzerland, Spain etc have the least undernourishment rates. 


## CASE I: COVID-19 VARIABLES by OBESITY RATE, and UNDERNOURISHED RATE
The first step in the analysis is to investigate the relationship between obesity rate and undernourished rate with the covid data attributes of every country in the dataset. The following sections presents the various approaches that have been used for analyzing the relationship and the insights obtained.

### Statistical Test
The following sections discusses the various statistical analysis done on the above mentioned data attributes to find out if there exist any significant correlations.

#### T-test

The t-test statistical tool from the python statistical package was used to analyze any significant difference in the values of covid data attributes among low and high obese countries.
The t-tests revealed that there exist significant difference among 'death rates' and 'confirmed rates' among countries with high obesity and that with low obesity. 
The output obtained from the t-test is displyed below.

![image](https://user-images.githubusercontent.com/25582927/145691372-4ab6cd63-bd74-4be0-9fa9-ad8181994019.png)

#### One way ANOVA

The one way anova test included in the stat package in the sklearn library was used to analyze the differnce between the covid attributes among the countries with low, mid and high under-nourishment. The resullts obtained after executing the one-way test is shown below.

![image](https://user-images.githubusercontent.com/25582927/145691540-533b7d2e-3a82-4d30-873c-3f54adb432a1.png)


### SCATTER PLOT WITH REGRESSION LINE -- OBESITY RATE

![COVID-by-Obesity](https://user-images.githubusercontent.com/51665593/145691763-faeecf52-a34f-4077-8da0-6fb8128f9aaf.png)

In the above scatter plot, the points represents the reationship between the obesity rate and the population of each countries. Each points are color encoded to identify points that represent confirmed, death or recovery rates. From the visualization and the regression lines fitted it can be seen that the rate of confired cases as well as recovered cases increases as the obesity rate increases. Also, from the the graph the points of recovery rate seems to be clustered around the minmal value, but as the obesity of the country crosses the 18 point mark the clustring of death points are found in surplus.


### SCATTER PLOT WITH REGRESSION LINE -- UNDERNOURISHED RATE

![COVID-by-Undernourished](https://user-images.githubusercontent.com/51665593/145691767-ce7d5600-1caf-4bff-8476-708f14e7a71b.png)

## CASE II: DIET VARIABLES by OBESITY RATE, and UNDERNOURISHED RATE

### Heatmap for Diet Variables and Obesity Rate

![Heatmap-Obesity-by-Diet](https://user-images.githubusercontent.com/51665593/145691777-643151d5-1bc7-4cd1-a9a0-49173547eaa6.png)

Using the Spearman's correlation test, we have considered all the diet variables and obesity rate to find the correlation among them. 

### Heatmap for Diet Variables and Undernourished Rate

![Heatmap-Undernourished-by-Diet](https://user-images.githubusercontent.com/51665593/145691783-bc069644-7c8c-47a4-97e4-6da24c2dc396.png)

Just like obesity rate, this heatmap is intended to find the correlation between undernourished rate and diet variables. 

### Individual Diet Insights

#### With respect to Obesity rate
![Diet-by-Obesity](https://user-images.githubusercontent.com/51665593/145691786-472ca03e-f6bd-4428-9cf6-f855052327e9.png)

We have considered the individual diet variables to extract the individuals' obesity rate. 

#### With respect to Undernourished rate

![Diet-by-Undernourished](https://user-images.githubusercontent.com/51665593/145691791-e8766bbd-cfe6-443b-88eb-ac2b59a8ca2e.png)

## SEMANTIC INFERENCES

In countries with fewer confirmed cases, when both the obesity and undernutrition rates are low, Therefore, it is important to have a healthy diet plan. For example, vegetable products, cereals, etc.  

## REFERENCES

* Coronavirus disease (COVID-19) advice for the public. World Health Organization; 2020. https://www.who.int/emergencies/diseases/novel-coronavirus-2019/advice-for-public  
* Cases in the U.S Centers for Disease Control and Prevention. 2020. https://www.cdc.gov/coronavirus/2019-ncov/cases-updates/cases-in-us.html  
* COVID-19 Open Research Dataset Challenge (CORD-19). https://kaggle.com/allen-institute-for-ai/CORD-19-research-challenge. Accessed 11 Dec. 2021.  



```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](/assets/images/pic1.png)
```
