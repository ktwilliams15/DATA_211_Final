# DATA 211 Final
#### Background
For the final project, I started by analyzing child abuse statistics in the United States. The original data contained the number of child abuse cases per state in 2018. As expected, the states with larger populations had more child abuse cases. Importing U.S. census data, I was able to find the number of children (under the age of 18) in each state. To standardize the data, I divided the total child abuse cases in each state by the number of children in each state. In order to grow understanding of child abuse, I decided to compare the percentage of child abuse to median income, unemployment rates, and the child fatality rate in each state. Looking at a heatmap of the correlations of these features, you can quickly see that there is not a strong relationship between any of these features. 

![Heatmap of Percentage of Child Abuse, Child Fatality Rate, Median Income, and Unemployment Rates](Correlation_Final.png)

#### Findings
Although the heat map does not show strong correlations, there were some interesting findings in the data. When comparing the ten states with the lowest median incomes, to the states with the highest unemployment rates, the highest child fatality rates, and the highest child abuse percentages, there was some overlapping. Interestingly, the states with the highest fatality rates and the states with the highest percentage of child abuse only had two states overlap. This may be interesting to look at further from a psychological perspective. Perhaps child abuse perpetrators want to avoid law enforcement engagements. The large disparity in power gives them confidence that the victim will remain silent and as long as the abuse does not escalate, the perpetrators can continue their habits of abuse without being discovered. 

[Child Abuse Percentages vs. Child Fatality Rates by State](https://ktwilliams15.github.io/abuse_perc/abuse_fatal.html)

On the other hand, the ten lowest median incomes and the ten highest unemployment ratios had four states overlap. Economically, it makes sense that a state with a higher unemployment ratio will have lower wages. Since the supply of workers is larger than the number of jobs, companies can pay workers less money because t
