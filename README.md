# Education
A project for Seattle University's DATA3320 class. <br>
Exploring if school performance on the SAT or ACT can be predicted by socioeconomic factors.

## Requirements

~




## Data

  The **EdGap Data Set** contains information about average ACT or SAT scores for schools and several socioeconomic characteristics of the school district from 2016. All socioeconomic data (household income, unemployment, adult educational attainment, and family structure) are from the Census Bureau’s American Community Survey.

[EdGap.org](https://www.edgap.org/#5/37.875/-96.987) report that ACT and SAT score data is from each state’s department of education or some other public data release. 

  The **School Information Data** is from the [National Center for Education Statistics](https://nces.ed.gov/ccd/pubschuniv.asp). This data set contains basic identifying information about schools.

The data set EdGap_data.xlsx can be accessed from the Github repository for DATA 3320 in the [education](https://github.com/brian-fischer/DATA-3320/tree/main/education) folder. 

The school information data set ccd_sch_029_1617_w_1a_11212017.csv is too large for Github and can be accessed from the dropbox link:
https://www.dropbox.com/s/lkl5nvcdmwyoban/ccd_sch_029_1617_w_1a_11212017.csv?dl=0


~

## Data Preparation

  To prepare the data for analysis, the following steps were taken:
    - converting data types as necessary
    - subsetting to data useful to our questions
    - renaming columns
    - joining the edgap and school info data into one frame
    - setting out of range values to NaN or deleting them
    - creating test and train splits
    - imputing any NaN values
    - finalizing the clean data sets
  
  You can find the file that preforms this preperation, named:
  The clean data files for the training and test splits are in the clean_data folder, named: education_clean_train.csv & education_clean_test.csv

~



