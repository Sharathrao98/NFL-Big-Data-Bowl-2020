https://github.com/Sharathrao98/NFL-Big-Data-Bowl-2020/blob/main/NFL-768x372.jpg?raw=true

# NFL Big Data Bowl 2020:

The annual sports analytics contest from NFL Football Operations challenges talented members of the analytics community – from college students to professionals – to contribute to the NFL’s continuing evolution in the use of advanced analytics.

As the NFL captures real-time data for every player, on every play, in every situation — anywhere on the field — the Big Data Bowl is the league’s next step in engaging the analytics community.

Contestants use traditional and Next Gen Stats to analyze and rethink trends and player performance, and to innovate the way football is played and coached.


## Methods of Analysis:

To address the challenges faced in solving the problem, we made use of predictive analytics to infer the effectiveness of an offensive team’s play by classifying the type of pass and determine a successful pass over an incomplete pass.
The following steps were followed in achieving the end result:
Data cleaning  was done with the help of pandas profiling which showed the insignificant columns and columns showing high cardinality which we eliminated.
Data visualization and Exploratory Analysis was done using Matplotlib and plotly.express to plot various graphs to analyse the different positions of players in the offensive team, their height-weight distribution, age group distribution and many more.
After Data visualization was done, lazy predict module was used to see the efficiency of various algorithms. Based on the results obtained from it, 4 algorithms namely Logistics Regression, Gradient Boosting Regressor, Random Forest and Bagging were executed.
Multiple inputs were given to the algorithms such as distance needed for first down, Team of offense, Game Quarter etc to determine the type of pass.
Based on the different parameters such as precision, recall, f1 score and accuracy, Gradient Boosting Regressor algorithm was found to have the highest f1 score.
