# Female Entrepreneurship Worldwide

*Sabrina Rubert, July 2020, Berlin*

## Content
* [Project Description](https://github.com/sabrinarubert/femaleEntrepreneurship#project-description)
* [Question & Hypotheses](https://github.com/sabrinarubert/femaleEntrepreneurship#question--hypotheses)
* [Dataset](https://github.com/sabrinarubert/femaleEntrepreneurship#dataset)
* [Workflow](https://github.com/sabrinarubert/femaleEntrepreneurship#workflow)
* [Organization](https://github.com/sabrinarubert/femaleEntrepreneurship#organization)
* [Links](https://github.com/sabrinarubert/femaleEntrepreneurship#links)

## Project Description
In general everybody knows tht there is still a gender gap in entrepreneurship worldwide, even though several studies actually demonstate the positive impact of female entrepreneurs on economic growth and development. I decided to dive deeper into the data of female versus male entrepreneurs and see how the current distribution looks like, as well as to find out what could be factors that support or rather influence female entrepreneurship.

## Question & Hypotheses
* How does the gender gap in entrepreneurship look like regarding the moste recent data?
* Which countries do especially great, which aren't that great?
* What kind of factors support or inhibit female entrepreneurship?

## Dataset
For the analysis I used publicly available data from the World Bank Data. The data about female & male entrepreneurs can be found [here](https://www.doingbusiness.org/en/data/exploretopics/entrepreneurship/gender#1). Also I looked at the Women Business and the Law Index data, which is also available on the World Bank Data website [(Link)](https://wbl.worldbank.org/en/wbl-data).

When downloading the data I realized that there were a lot of countries within the dataset without any numbers. I had to remove a few countries were there was no data for the most recent year as I wanted to especially focus on that. Furthermore I had merge the Women and Business and the Law Index data with the entrepreneurship data.

## Workflow
The following workflow was implemented:

1. Choosing the dataset
2. Deciding in the focus for the project
3. Data cleaning and wrangling
4. Analysis
5. Conclusions
6. Visualization & Presentation

## Links
This repository is divided into different folders.

**Data Cleaning & Analysis**
* Notebook: [World Bank data - cleaning and analyzing](https://github.com/sabrinarubert/femaleEntrepreneurship/blob/master/Analysis/World%20Bank%20data%20-%20cleaning%20and%20analyzing.ipynb)

**Presentation**
* Google Slides: [200710_InsightsEntrepreneurship](https://github.com/sabrinarubert/femaleEntrepreneurship/blob/master/Presentation/200710_InsightsEntrepreneurship.pdf)

**Definition of terms**
* Notebook: [Definition of terms](https://github.com/sabrinarubert/femaleEntrepreneurship/blob/master/Other/Definition%20of%20terms.ipynb)

## Analysis
**Share of business owners**

By looking at the descriptive statistics for the share of business owners within the year 2018, I found out that less than one-third of business owners are women in the vast majority of economies. Even though in those countries, where the share of female business owners is higher, there can still a gender gap be seen. On the first place with regards to the share of female businss owners is Romania, the last place takes Afghanistan.

**Share of sole proprietors**

The gender gap is not as large as it was with the business owners, still there in fact no country in the year 2018 where the share is similar or even highert to the male-owned sole propriertors. With regards to the share of female proprietors Jamaica is on the first place. Afghanistan again is the country with the lowest share. 

**Entrepreneurship and country income group**

As several studies state that gender gaps in female business entry and ownership are associated with substanital losses to national income and economic development, I decided to also have a deeper look at the different income groups of the countries and see how they compare with regards to the gender gap.

The gender gap is in every income group clearly visible. It is even higher in high and upper-middle income group countries. In low income economies women are proportionately less likely to start a business at all.

**Regression Analysis**

As I found out from the descriptive statistics that there are differences in female entrepreneurship between different countries and especially between those with a low income, I wanted to check which factors are relevant and have an influence on female entrepreneurship:

As gender gaps in female business are often reflected by disparities in women's legal rights (for example use of property, going to court, building credit etc.), I found the Women Business and the Law Index, which measures those factors in various countries and gives out an index score.

To test my assumptions I did a regression analysis to see if on the one hand the income country and on the other hand the Women Business and the Law Index influences female entrpreneurship.

The Analysis showed a higher r-squared for the factor of the income group (0.325) and a smaller one for the women business and the law index (0.193).Therefore it showed that the income of a country has a higher influence on the proportion of female entrepreneurs than legal disparities.

## Conclusions
The gender gap remains high around many economies around the world. The income of the country has a higher influence on the proportion of female entrepreneurship than legal disparities. This suggests that women indeed have the opportunity to build businesses and are not held back by legal disparities. Still, there must be other factors that have an influence on female entrepreneurship as for example education or access to financial institutions. 

## Limitations
There is an overall lack of data with regards to female entrepreneurship. That makes it hard to look for example at the share of female entrepreneurship over time (not all countries provide data every year). More research must be done to have a more detailed picture about that topic.

Furthermre it would be interesting to look at other factors that have an influence on female entrepreneurship as for example education or access to financial institutions.

