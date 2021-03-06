Analysis of Teachers’ Recruitment in Saudi Arabia Between 1437 and 1440
================
areej mohamed othman
6 March 2021

Group Number: team1

Group Members’ Names (IDs):

1.  aljawhara khalid(2201001960) – Team Leader 2asrar
    almutairi (2201000537) – Member 1 3Ibtsam faleh.(2201002692) Elham
    khatim(2201001444)– Member 2 4alaohoud faleh (2201002394) 5alkadi
    mutlaq (2201003964)

## Loading Libraries

Ensure you have the `tidyverse` and `readxl` packages installed by
running the 2 lines of code below. Both the team leader and members
should run the code below in the console of rstudio.

We then need to load the data from the MS Excel (.xlsx) file, named
teachers\_data.xlsx, to the R environment for processing.

*Note: Only Team Leader should run the code below*

``` r
tdata <- read_excel("teachers_data.xlsx")
```

# Wherever you see the text ‘\#Add some code’, it means you should delete the comment and add your code for the task.

# 2 Marks will be deducted for every deadline missed.

## Task 1

``` r
tdata = rename(tdata,  administrative_regions = "المنطقة الإدارية")
tdata = rename(tdata,  school_level = "المرحلة")
tdata = rename(tdata,  authority = "السلطة")
tdata = rename(tdata,  Office_of_Education = "مكتب التربية")
tdata = rename(tdata,  sex = "الجنس")
tdata = rename(tdata,  School_type = "نوع المدرسة")
tdata = rename(tdata,  Type_of_education = "نوع التعليم")
tdata = rename(tdata,  school_system = "نظام الدراسة")
tdata = rename(tdata,  Saudi_teacher = "معلم سعودي")
tdata = rename(tdata,  Non_Saudi_teacher = "معلم غير سعودي")
tdata = rename(tdata,  Teachers = "معلمين جملة")
tdata = rename(tdata,  the_year = "السنة")
```

Team Leader should *Knit, commit, and push changes to GitHub with an
appropriate commit message. Make sure to commit and push all changed
files so that your Git pane is cleared up afterwards.*

## Task2

Next Team Member should *Pull the changes made by Team Leader before
proceeding.*

1.  What are the different administrative\_regions (Al-Mandaqah
    Al-idariyyah) found in the data?

``` r
#Add some code
```

Comments about your answer:

1.  Based on your knowledge of the administrative regions in Saudi
    Arabia, is there any region that has not recruited any teacher
    during the period under review (1437 - 1440 Hijri)? List the Saudi
    regions shown in the data.

``` r
#Add some code
```

Comments about your answer:

The Team Member should *Knit, commit, and push changes to GitHub with an
appropriate commit message.*

## Task3

The Next Team Member should *Pull the changes made by Member 1 before
proceeding.*

1.  Saudi Arabian education is divided into different stages/levels
    (Al-Marhala), list the different levels showed in the data in
    descDEADLINE: ENDing order of frequency. (4 points)

``` r
#Add some code
```

Comments about your answer:

1.  Which level recruit the most teachers? (4 points)

``` r
#Add some code
```

Comments about your answer:

The Team Member should *Knit, commit, and push changes to GitHub with an
appropriate commit message.*

The Next Team member should *Pull the changes made by Team Leader before
proceeding.*

1.  Plot the graph of region versus number of **Saudi** teachers
    recruited over the period. (4 points)

``` r
#Add some code
```

Comments about your answer:

1.  Plot the graph of region versus number of **Non-Saudi** teachers
    recruited over the period. (4 points)

``` r
#Add some code
```

Comments about your answer:

1.  Plot the graph of region versus number of **all teachers** recruited
    over the period. (4 points)

``` r
#Add some code
```

Comments about your answer:

The Team Member should *Knit, commit, and push changes to GitHub with an
appropriate commit message.*

## Task 4

The Next Team member should *Pull the changes made previously before
proceeding.*

1.  How many boys and how many girls schools are listed in the data? (4
    points)

``` r
#Add some code
```

Comments about your answer:

1.  Between boys and girls schools, which recruit more teachers? (4
    points)

``` r
#Add some code
```

Comments about your answer:

1.  What is the correlation between recruitment at boys schools and
    recruitment of girls schools? (4 points)

``` r
#Add some code
```

Comments about your answer:

The Team Member should *Knit, commit, and push changes to GitHub with an
appropriate commit message.*

## Task 5

The Next Team member should *Pull the changes made previously before
proceeding.*

1.  How many teachers are recruited each year, 1437, 1438, 1439, and
    1440?

``` r
#Add some code
```

Comments about your answer:

1.  Which region recruited the most teachers in each of the years under
    review? (4 points)

``` r
#Add some code
```

Comments about your answer:

1.  Plot the graph of number of teachers recruited vs the number of
    schools in an administrative region? What type or relationship exist
    between the two variables? (4 points)

``` r
#Add some code
```

Comments about your answer:

The Team Member should *Knit, commit, and push changes to GitHub with an
appropriate commit message.*

## If you are here, then congratulations!! You have completed the DSC 200 course project.
