# Surfs_up

## Overview

W. Avy is an investor who is concerned about the weather in Oahu because of his previous investment experience. He has requested analytics on a weather data set he has from Oahu to better inform his decison to invest in a brillant idea of opening a "Surf n Shake" shop which will serve surf boards and ice cream to tourists and locals of Oahu. We are going to analyse the data using Python, Pandas functions and methods, and SQLAlchemy.


## Results
From the analysis in the month of June, the average temperature was around 75F, the minimum temperature was at 64F.

Decemeber saw an avearge temperature of around 71F and the minimum temperature was at 56F

Maximum temperature for June and Decemeber were 85F and 83F respectivelty. 


Figure1 and Figure2 shows a table of the summary statistics of temepratures in June and December.
![figure1](https://github.com/Elfreda2019/Surfs_up/blob/main/resources/June_temp.png)
Figure1
![figure2](https://github.com/Elfreda2019/Surfs_up/blob/main/resources/December_temp.png)
Figure2
## Summary

Temperatures are between 64F and 84F in June and 56F and 83F in December. Decemember temperatures is skewed to the right.

### 
Will like to investigate more into the distribution of the temperatures by plotting histogram using the following queries for both June and December.

* results_list_df.plot.hist(bins=12)
* plt.tight_layout()
