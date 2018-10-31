## Last Week's Accomplishments

> In this section, you can write about what you accomplished in the previous week.

This week I pushed end of day stock data from 35 tickers into our database. I got a PR accepted containing two main programs:
  - One to formulaically add the data to the postgres server
  - and another to add only stock data starting at the date of the data that is already in the db. This is key to avoid duplicate data.

## This Week's Plan

> In this section, you can write about what you have planned for next week.

Since the old data is in the database now, I need to work in Airflow to set up a scheduled data pipeline. In the context of this project, pipeline means to schedule the program that adds a smaller subset of stock data to the database to run every day after the market closes.

## Anything Blocking?

> In this section, you can write about any blockers that you are having trouble in the project.

Nothing is blocking. In terms of the overarching goals of the project, we are waiting on the web application folks to have a functioning frontend before moving forward with more functionality.

## Notes

> This is an optional section for any sort of information that does not fall under any of the other categories.
