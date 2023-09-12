[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/4mvcwNfD)
# WhatDay

This simple Android app asks the user for a date in the Gregorian calendar and returns the day of the week for that date.

Using the Java Gregorian Calendar API.

All the suggestions given by the google accessibility scanner have been considered while designing this app.

Functionalities:
1. It returns the day of a given valid date.
2. Identifies invalid dates including:
   1. Using nonnumeric character in dates
   2. Invalid year/month/date value
   3. Months with number of days=31 and months with number of days = 30
   4. Leap years according to Gregorian Calendar

Assumptions/Restrictions:
1. Years are of size 4 digits only
2. accepted year values are between 1000 and 2023(years of the future are not accepted)
3. There is no auto clear in the keyboard, we have to clear our input manually to put in new input
