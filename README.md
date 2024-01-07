# pandas-challenge
#### Made by Lucas Ulbrich on the 06th of January 2024

## Challenge Background

You are the new Chief Data Scientist for your local government area. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyse the area-wide standardised test results. You'll be given access to every student's maths and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

## Files

## Sources

Below are a list of sources for the advanced pandas functions I have used:
School Summary:

* `.apply(lambda x:`, and `.assign(lambda x:` to find the percentage of scores over 50: https://www.geeksforgeeks.org/applying-lambda-functions-to-pandas-dataframe/
* `.gt` the greater than function for the overall percent above 50: https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.gt.html

Maths scores by year and reading scores by year:

* `.eq` the equals function to collect data specific to a year: https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.eq.html