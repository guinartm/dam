# Developers Bonus Report 
### Summary of the analysis:
After the analysis of August and September reports insight identified are:

  - An unusual high number of queries failed during the afternoon of 18th of August. This is not related to a higher nº of users using the solution.
    - Developers were supposed to increase the performance during August. After some qualitative research, developers state the reason of the issue is linked to a bug they had already identified in previous months and now they have finally identified the rootcause and applied a permanent fix to it. This is most likely the cause of some clients complaining about errors in the solution (Assumption)
  - The % of failed queries has decreased from 1.5% to 1% from August to September.
  - Excluding the 18th of August outlier, the nº of failures has still decreased by around 2000 failures.
  - Evening is the range of the day where there are more failures summing failures in both months.

### Limitations:
- Access to July report or waiting for October report would provide better insights on the evolution in the decrease of failed queries.

### Final conclusions and recommendations:
- Failed queries have decreased from one month to the other. Developers have identified the repeated issue rootcause and applied a permanent fix.
- Developers have slightly improve the performance of the solution, seeing a decrease in total failed queries during September even if we exclude the issue of August 18th.
- With deeper information on the reasons of failure in the queries, I could give the developers the right insights to better target the reasons of failure and action them through targeted fixes and achieve a % of failed queries smaller than 1% of the total queries done, especially having identified how evening seems to be the period of the day with more failures summing failures in both months. 
- With the information already provided you can make a decision, however further analysis with a bigger sample of queries done in the tool from previous and even next months will give you more solid arguments on your decision.

### For more especific information about the analysis:
https://docs.google.com/spreadsheets/d/1FLzedzh67hWgfHKLOs-RoXG-ZoCUzwa04OLOwA1c9L4/edit?usp=sharing
