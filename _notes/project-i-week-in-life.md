---
title: "Project I: Data Dictionary, A Week in the Life"
author: "Taylor Arnold"
---

**[NOTE: DUE TO THE MISSED CLASS, YOUR PROJECT GRADE WILL ALSO BE
USED IN PLACE OF YOUR FIRST MIDTERM**

**Due**: 2018-09-27 (start of class)

**Starter code**: <a href="https://raw.githubusercontent.com/statsmaths/stat209-f18/master/projects/project-i.Rmd" download="project-i.Rmd" target="_blank">project-i.Rmd</a>

**Rubric**: [project-i-rubric.csv](https://github.com/statsmaths/stat209-f18/blob/master/projects/project-i-rubric.csv)

The overarching goal of the first project is to collect a data set, produce a
data dictionary, and provide a basic exploration of the variables from your
data.

Specifically, you will be collecting data about a specific week in your life.
You will be creating three linked datasets with the following information:

- one dataset where the unit of observation is one hour, indicating what you
were doing and where you were at the start of the hour. This will have a total
168 rows (24 * 7) where you will record:
    - your name (same on every row)
    - the time
    - activity tag
    - location tag
    - one other variable of your choosing
- one dataset of places that has variable for:
    - location tag (one match for each record in your hourly dataset)
    - latitude
    - longitude (use Google maps or similar for help with this one)
    - one other variable of your choosing
- one dataset of activities:
    - activity tag
    - ranking of how much you enjoy this activity, from 1 (hate it) to 10 (love it)
    - one other variable of your choosing

**Note**: It may be that some of the data I would like you to collect is quite
sensitive and personal. Part of the point of this project is to understand how
invasive something as simple as your weekly activities can be in practice. Of
course, I don't want you to actually share information you are at all
uncomfortable with. *Feel free to make up reasonable surrogates for any
activities or locations for time points that you would rather not publicly
share with the class.* If you have further questions or concerns, please let me
know as soon as possible.

Here are template files for these three datasets (they fill in the same
activity, sleeping, for every hour):

- <a href="https://raw.githubusercontent.com/statsmaths/stat209-f18/master/projects/project-i/hourly.csv" download="hourly.csv" target="_blank">hourly.csv</a>
- <a href="https://raw.githubusercontent.com/statsmaths/stat209-f18/master/projects/project-i/places.csv" download="places.csv" target="_blank">places.csv</a>
- <a href="https://raw.githubusercontent.com/statsmaths/stat209-f18/master/projects/project-i/activities.csv" download="activities.csv" target="_blank">activities.csv</a>

Be sure to download and fill out the <a href="https://raw.githubusercontent.com/statsmaths/stat209-f18/master/projects/project-i.Rmd" download="project-i.Rmd" target="_blank">project-i.Rmd</a> starter code, it asks you to create a data dictionary for the three records.
By the deadline you should have submitted the three CSV files and project
Rmd file.

