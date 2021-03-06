#Using Kickstarter dataset to analyze the relation in campaign outcomes.

##The analysis was performed by comparing  
1. the total number of theater outcomes (successful/failed/cancelled) based on campaign launched month.
2. the successful or failed percentage of campaign based on their goal amount.
 
 
###Challenge/limitation with dataset
- The dataset holds the data intermittenly and lacks in some months before Apr 2014. 
- The total number of outcomes in corresponding months may be skewed. 
- There are only two years (2015 and 2016) that have fullset data and may not be enough samples to establish the year over year or month by month trend for forecasting the future outcomes.


##Outcomes based on Launched Date
- The month of May records the highest successful number of theater outcomes and December seems to be the least favorable month to launch promotion.
	- [Theater outcomes based on launched date](https://github.com/Yunaka1269/kickstarter-analysis/blob/master/Theater_Outcomes_vs_Launch.png)
- Althought it bumped up from 2014 to 2015, the number of outcomes has a trend of declining over the time.
	- [Theater outcomes transition since 2014](https://github.com/Yunaka1269/kickstarter-analysis/blob/Other/Theater_Outcomes.png)


##Outcomes based on Goal
- The trend is the higher the goal amount, the lower the successful percentage. 
	- [Outcomes based on Goal](https://github.com/Yunaka1269/kickstarter-analysis/blob/master/Outcomes_vs_goals.png)
- Descriptive statistic shows followings that mean, median, standard  deviation, and IQR are higher in failed campaign goal than successful ones.  
	- [Descriptive Statistic](https://github.com/Yunaka1269/kickstarter-analysis/blob/Other/Descriptive_Statistic.png)
- However, almost 85% of *play* campaigns are targeted at goal amount between $1 and $4,999 so the percentage gets fluctuated higher by 1 result in campaign that targets higher than $10,000. 
	- [Outcomes based on goal](https://github.com/Yunaka1269/kickstarter-analysis/blob/Other/Outcomes_vs_goals2.png)
	

###Possible tables
- *Theather* successful outcomes had increased three years in a row in April while other months had not, and also April records the third highest pledged total amount. 
- [Theater outcomes change by month](https://github.com/Yunaka1269/kickstarter-analysis/blob/Other/Theater_Outcomes_Comparison_by_Year.png)
- [Theater outcomes with pledged total](https://github.com/Yunaka1269/kickstarter-analysis/blob/Other/Theater_Outcomes_vs_Launch2.png)
	- It may be better to launch the promotion in April than May.
