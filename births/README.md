### U.S. births data

The raw data behind the story [Some People Are Too Superstitious To Have A Baby On Friday The 13th](http://fivethirtyeight.com/features/some-people-are-too-superstitious-to-have-a-baby-on-friday-the-13th/)

There are two files:

`US_births_1994-2003_CDC_NCHS.csv` contains U.S. births data for the years 1994 to 2003, as provided by the Centers for Disease Control and Prevention's National Center for Health Statistics

`US_births_2000-2014_SSA.csv` contains U.S. births data for the years 2000 to 2014, as provided by the Social Security Administration

Both files have the following structure:

Header | Definition
---|---------
`year` | Year
`month` | Month
`date_of_month` | Day number of the month
`day_of_week` | Day of week, where 1 is Monday and 7 is Sunday
`births` | Number of births

That's it for the guided steps. Here are some suggestions for next steps:

## Write a function that can calculate the min and max values for any dictionary that's passed in.
## Write a function that extracts the same values across years and calculates the differences between consecutive values to show if number of births is increasing or decreasing.
For example, how did the number of births on Saturday change each year between 1994 and 2003?
## Find a way to combine the CDC data with the SSA data, which you can find here. Specifically, brainstorm ways to deal with the overlapping time periods in the datasets.
