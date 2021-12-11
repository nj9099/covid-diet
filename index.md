## Covid - 19 and World Nations' Diet Plans

### Introduction
Covid-19 pandemic has brought the world to a state of uncertanity and confusion. The impacts of the covid has affected the health, social and economic well-being of people in all the countries around the world. The first covid case ever was reported in the China on December 2019, since then the pandemic has never left face of earth and continues to be a threat worldwide causing havoc in the lives of millions. 

### Exploring Dataset
The dataset for the project was downloaded from  the Kaggle(include the HTTP link here) website. The dataset records all the importand diet components or food variables of a counrtry along with its corresponding covid related information such as 'recovered', 'deaths', 'active' and 'total population'. The dataset records the value of diet variables as percentage intake of that particular food item. For example if a value corresponds to 'Animal Fats' says 0.19, it means that the proportion of animal fat in the food consumed by that country is 19%. The dataset records the values for 170 countries. The data regarding the covid was collected from the Johns Hopkins Center for Systems Science and Engineering CSSE website.

### Data Pre-processing
The dataset recorded the values of total confirmed cases, recovered cases, active cases and total deaths as percentage of the total population. In order to make meaningful statistical analysis the variables need to be converted to the real number format, which was done by multiplying the values with the corresponding population data. Moreover, the dataset also contains inconsistent data which got removed by eliminating those rows that contained them. 

### Visualizations
Visulaizations on the dataset was mainly done for exploring the various attributes in the dataset and to make visual analysis based on them. 

![pic1](https://user-images.githubusercontent.com/25582927/145689209-ca440350-f45f-4a20-8a79-93785a0e46b3.png)

In the above scatter plot, the points represents the reationship between the obesity rate and the population of each countries. Each points are color encoded to visualize if the it represents confirmed, death or recovery rates. 

You can use the [editor on GitHub](https://github.com/noelgith/covid-diet/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for



# GOALS

The goal is to find the diet which will help to keep you healthy in this COVID-19 pandemic.

# STEPS

## EXPLORATORY DATA ANALYSIS

### BASIC VISUALIZATIONS
Country vs. Obesity Rate
Which country has lowest and highest obesity rate?

![Country-by-Obesity](https://user-images.githubusercontent.com/51665593/145691362-4070c141-9d0f-4435-a566-02289c6d1b15.png)


Country vs. Undernourished Rate
Which country has lowest and highest undernourished rate?


![Country-by-Undernourished](https://user-images.githubusercontent.com/51665593/145691367-65b1e282-588b-4aa0-b16c-e472035bad3a.png)


## DATA CLEANSING
## DATA TRANSFORMATION / DATA SPLITTING
## INSIGHTS & VISUALIZATIONS


# CASE I: COVID-19 VARIABLES by OBESITY RATE, and UNDERNOURISHED RATE

## STATISTICAL TESTS

### T-test
### One way ANOVA

## VISUALIZATIONS

### SCATTER PLOT WITH REGRESSION LINE -- OBESITY RATE

![COVID-by-Obesity](https://user-images.githubusercontent.com/51665593/145691378-6d021bb5-a8ca-4012-ac23-67ca7c7d85b0.png)

### SCATTER PLOT WITH REGRESSION LINE -- UNDERNOURISHED RATE

![COVID-by-Undernourished](https://user-images.githubusercontent.com/51665593/145691382-1a52ae55-1760-45ae-89e0-904b1f1c9586.png)


# CASE II: DIET VARIABLES by OBESITY RATE, and UNDERNOURISHED RATE

## STATISTICAL TEST

### SPEARMAN'S CORRELATION TEST
### HEATMAP
> Obesity Rate

![Heatmap-Obesity-by-Diet](https://user-images.githubusercontent.com/51665593/145691395-c12c371e-a1ba-4e3f-875c-68277c1bd7b4.png)



> Undernourished Rate


![Heatmap-Undernourished-by-Diet](https://user-images.githubusercontent.com/51665593/145691397-9ed95d8e-74a0-4316-a1c5-44cc9b79ca2b.png)


## VISUALIZATIONS

![Diet-by-Obesity](https://user-images.githubusercontent.com/51665593/145691407-581f7d2a-e540-405a-8f9d-059037fff88d.png)

![Diet-by-Undernourished](https://user-images.githubusercontent.com/51665593/145691409-b3a75971-d5eb-4994-b19d-246a9b5ddaa4.png)


# SEMANTIC INFERENCES

In countries with fewer confirmed cases, when both the obesity and undernutrition rates are low, Therefore, it is important to have a healthy diet plan. For example, vegetable products, cereals, etc.  
Avoid eating meat and drinking alcoholic beverages to avoid becoming susceptible to COVID.  
The lower the mortality rate, the healthier the diet.  



--------------------------------------------------------------------------------------------------------------------------

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
