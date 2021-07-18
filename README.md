CASE STUDY -: Weather_Case_Study

Table of Content-:

*Demo Overview

*Pandas Methods which are used in these project

*Graph which are used

*Workdone

*Conclusion

*Result

1)Demo Overview-: LINK-:(https://drive.google.com/file/d/15lovKEFNmgysHpDpvI_jcHzJ7cbjpG4V/view?usp=sharing)

2)Pandas Methods which are used in these project-: 

* info(),desribe(),isna(),sum() 

* value_counts(),groupby()

* nunique(),max(),min(),shape(),std(),var(),contains()

3)Graph which are used-:

->For plotting i have seaborn

* Heat map

4)Workdone-:


*I used info() to get the basic information of our dataset

*I used describe() method to get descriptive statistics of our dataset

*I used mean() to get the average of data in the Columns

*I used max() and min() to get the maximum value and minimum value with respect to columns.

*I used nunique() to count the number of unique elements.

*I used groupby() where i need the reference of some other column.

*I used std() and var() for standard deviation and variance respectively



5)Conclusion-:

**By the above analysis done, we can conclude that,

->Range of wind speed is from 0 to 90.

->Weather conditions are fog,cloudy,rainy,snow,drizzle etc.

->When we see the average then for clear we got 0 to 12,for cloudy and drizzle we    got 15 to 18,for fog we got 10 to 12 and for ice pellets we got 18 to 22 wind      speeds.

->All columns have avg relationship with them but,relative humidity and visibility  have inverse relationship i.e if relative humidity increases then visibility   decreases and viseversa and relationship between temperature and dew point    temperature is very high.

->When relative humidity is in range 60 to 65 the weather is clear,when relative humidity is in range 66 to 70 the weather is cloudy,when relative humidity is in range 85 to 100 then weather is drizzle,when relative humidity is in range 90 to 95 the weather is fog or ice pellets in air.

6)RESULT-:

In the light of evidence, we came to a result that when relative humidity increases then visibility decreases and when relative humidity decreases then visibility increases this is because when relative humidity is high then percentage of water in air is high due to this we will not be able to see properly.Hence we can say that when rel humidity is more, visibility will be less, so aviod using vehicles.
