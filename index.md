## Covid - 19 and World Nations' Diet Plans

## Objective

The project is intended to find the suitable diet pattern that helps to minimize the chances of getting the covid disease. 

### Exploring Dataset
The dataset for the project was downloaded from the Kaggle(include the HTTP link here) website. The dataset records all the importand diet components or food variables of a counrtry along with its corresponding covid related information such as 'recovered', 'deaths', 'active' and 'total population'. The dataset records the value of diet variables as percentage intake of that particular food item. For example if a value corresponds to 'Animal Fats' says 0.19, it means that the proportion of animal fat in the food consumed by that country is 19%. The dataset records the values for 170 countries. The data regarding the covid was collected from the Johns Hopkins Center for Systems Science and Engineering CSSE website.
Additionaly, the dataset also records the values of undernourishment rates and obesity rates of each of the countries in the dataset.

### Data Pre-Processing
The dataset recorded the values of total confirmed cases, recovered cases, active cases and total deaths as percentage of the total population. In order to make meaningful statistical analysis the variables need to be converted to the real number format, which was done by multiplying the values with the corresponding population data. Moreover, the dataset also contained inconsistent data points which got removed by eliminating those rows that contained those points. 

## Exploratory Data Analysis

Country vs. Obesity Rate

![Picture7](https://user-images.githubusercontent.com/25582927/145690043-9701ccd4-ae1c-4da9-a301-e892940ea86c.png)

The above horizontal bar plot visualization helps to understand the obesity rates of the various countries. The country with the highest obesity rate is USA while the country with the lowest obesity rate is Vietnam.

Country vs. Undernourished Rate



![Picture8](https://user-images.githubusercontent.com/25582927/145690389-be1f5d54-77a2-4137-b3f9-f271bad9375a.png)

From the graph it can be clearly understood that the country with the most undernourishment rate is Zimbabwe followed by Zambia and Yemen. While, countries like USA, UK, Sweden, Switzerland, Spain etc have the least undernourishment rates. 


## CASE I: COVID-19 VARIABLES by OBESITY RATE, and UNDERNOURISHED RATE
The first step in the analysis is to investigate the relationship between obesity rate and undernourished rate with the covid data attributes of every country in the dataset. The following sections presents the various approaches that have been used for analyzing the relationship and the insights obtained.

## Statistical Test
The following sections discusses the various statistical analysis done on the above mentioned data attributes to find out if there exist any significant correlations.

#### T-test

The t-test statistical tool from the python statistical package was used to analyze any significant difference in the values of covid data attributes among low and high obese countries.
The t-tests revealed that there exist significant difference among 'death rates' and 'confirmed rates' among countries with high obesity and that with low obesity. 
The output obtained from the t-test is displyed below.

![image](https://user-images.githubusercontent.com/25582927/145691372-4ab6cd63-bd74-4be0-9fa9-ad8181994019.png)

#### One way ANOVA

The one way anova test included in the stat package in the sklearn library was used to analyze the differnce between the covid attributes among the countries with low, mid and high under-nourishment. The resullts obtained after executing the one-way test is shown below.

![image](https://user-images.githubusercontent.com/25582927/145691540-533b7d2e-3a82-4d30-873c-3f54adb432a1.png)


## VISUALIZATIONS

### SCATTER PLOT WITH REGRESSION LINE -- OBESITY RATE
### SCATTER PLOT WITH REGRESSION LINE -- UNDERNOURISHED RATE

# CASE II: DIET VARIABLES by OBESITY RATE, and UNDERNOURISHED RATE

## STATISTICAL TEST

### SPEARMAN'S CORRELATION TEST
### HEATMAP
> Obesity Rate
> Undernourished Rate

## VISUALIZATIONS



# SEMANTIC INFERENCES

Fetch from the presentation.


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

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/noelgith/covid-diet/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
