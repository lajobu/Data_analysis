# :star: Rent expenses:

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

In this project I will analize the `rent expenses` during the `two years` period I was `living in Warsaw (Poland)`.

I was living in `Mokotow` area, the apartment had `55 square meters`, with `two rooms`, `terrace` and `garden`. During this period, the landlord sent me every monmth an excel file with all the details about the renting expenses, such as heating, electricity...

All this expenses together with the temperature data extracted from the website: `https://rp5.ru/` will be analized, in order to extract some insights.

## Graphs and insights:

### Correlation:

![alt text](https://github.com/lajobu/Data-analysis/blob/master/2%20Renting%20expenses/Graphs/Screenshot%202020-09-25%20at%2012.14.39.png)

* In the above representation it can be seen the `correlation between the variables`. It looks like there is `high negative correlation` between the variables `heating and temperature` and between `average temperature and hot water`. On the other hand, there is `high positive correlation` between `cold water and temperature`, and between `hot water and heating`.

* Next, this variables with high positive and negative correlation are going to be `analized together`. In order to be able to be compared the `data was normalized`, in order to be able to compare the trend.

#### High negative correlation:

![alt text](https://github.com/lajobu/Data-analysis/blob/master/2%20Renting%20expenses/Graphs/Screenshot%202020-09-25%20at%2012.13.48.png)

* In the above graph one can find the graph representation of the  `average temperatures and heating`. It is clear that there is a `really high negative correlation`. This has sense, because when it is could with lower temperature, normally the heating is used more, hence the heating expense increases.

![alt text](https://github.com/lajobu/Data-analysis/blob/master/2%20Renting%20expenses/Graphs/Screenshot%202020-09-25%20at%2012.14.19.png)

* In this case between the variables `average temperature and hot water` there is also marked negative correlation. This also has sense, because normally the hot water is used mostly when the temperatures are lower.

#### High positive correlation:

![alt text](https://github.com/lajobu/Data-analysis/blob/master/2%20Renting%20expenses/Graphs/Screenshot%202020-09-25%20at%2012.14.07.png)

* Regarding the positive correlation. Firstly, between the variables `average temperature and cold water`, looks like are going together, when one is growing the other is doing the same, the same thing when decreasing. There are two factors to explain this, the first one is that in summer when there are higher temperatures the water is used more than the hot one to take for example a shower. On the opther hand, I mentioned before that the house had garden, hence during summer it was needed to put water there, hence it is normal that the cold water expenses increased.

![alt text](https://github.com/lajobu/Data-analysis/blob/master/2%20Renting%20expenses/Graphs/Screenshot%202020-09-25%20at%2012.14.26.png)

* The same positive relationship occurs between `hot water and heating`. This is because the heating and the hot water is used to not be cold during the winter, or when the temperatures are low.

### Analysis by months:

#### Boxplot:

![alt text](https://github.com/lajobu/Data-analysis/blob/master/2%20Renting%20expenses/Graphs/Screenshot%202020-09-25%20at%2011.30.04.png)

* In this boxplot it can be seen the four main variable expenses `heating`, `hot water`, `cold water`and `electricity`. The `heating` is the expense that has the `greatest variation`, also it has the `lowest average`. On the other hand, the `cold water` and `electricity` have `small variation`, in the case of the last one, it has the `higuest average`.

#### Pie charts:

![alt text](https://github.com/lajobu/Data-analysis/blob/master/2%20Renting%20expenses/Graphs/Screenshot%202020-09-25%20at%2011.30.19.png)

* In this representation it can be find twelve pie chart for each month. It represents the percetage of `contribution to the monthly total expenses`.
