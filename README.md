# Education
A project for Seattle University's DATA3320 class. <br>
Exploring if school performance on the SAT or ACT can be predicted by socioeconomic factors.


## Description

<ul>
  <li>Processed and prepared raw .csv data in Google Colabratory, including subsetting data and creating and training test splits</li>
  <li>To analyze the relationship between school SAT/ACT performance and socio-economic factors, various regression models with different factors were created to find the best predictors.</li>
</ul>

  This project explores whether school performance on the SAT or ACT be predicted by socioeconomic factors. Using school's average scores and a number of socioeconomic data points (ex. median income), that data was cleaned to enable the making of linear regression models. <br>
  Work was done to find the most optimal set of socioeconomic predictors of ACT scores, which ended up finding that the number of students on free/reduced lunch and the rate of unemployment increases, and percent of adults with a college degree decrease
the average ACT/SAT scores decrease.  <br>
  Adding state as an additional categorical predictor was also explored, but was found to be a marginal improvement.

~

## Requirements


  Google Colabratory

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

  To prepare the data for analysis, the following steps were taken: <br>
    - converting data types as necessary <br>
    - subsetting to data useful to our questions <br>
    - renaming columns <br>
    - joining the edgap and school info data into one frame <br>
    - setting out of range values to NaN or deleting them <br>
    - creating test and train splits <br>
    - imputing any NaN values <br>
    - finalizing the clean data sets <br> <br>
  
  You can find the file that preforms this preperation, named: education_data_preparation.ipynb <br>
  The clean data files for the training and test splits are in the clean_data folder, named: education_clean_train.csv & education_clean_test.csv. Training and testing data files for the additional state question are called state_data.csv and state_data_test.csv respectively.

~

## Analysis

  To analyze our clean data, I broke our larger question into relevent sub questions. I then went about answering those questions by creating regression models with all possible predictor variables, each one individually, and finding the best subset of predictor variables. An additional question was also posed in relation to the Pacific Northwest state of Washington and the Midwest state of Illinois about whether adding the region as a predictor would improve the model. <br> <br>
  
  You can find the analysis notebook named: education_analysis.ipynb

~ 

## Author

  CM Denault
  
~

## License 

  no specific license, feel free to replicate / use while crediting.

