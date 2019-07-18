# reshape_ramen: jihan mcKenzie and mina bansal 
### reshaping ramen and world happiness data

Proposal: Compare country happiness ratings to ramen ratings.

Hypothesis: Countries with high ramen ratings have a low happiness index

Questions that can be answered with dataset:
1. Does a higher ramen rating correspond with a lower happiness rating?
2. Does the number of ramen brands in a country correspond to low GDP?
3. 

# Final Report

### Extract
We extracted Ramen ratings data from Kaggle which was gathered from https://www.theramenrater.com/.  We also extracted data from the UN's World Happiness Report 2017.

### Transform
To clean the Ramen csv file, we had
  a.) drop the neccessary columns
  b.) convert the dataframe objects to floats so we could run aggregate functions
  c.)re-set the index for our dataframe before merging
  d.)sort values ascendingly to identify countries before merging 

### Load


At the end of the week, your team will submit a Final Report that describes the following:

* **E**xtract: your original data sources and how the data was formatted (CSV, JSON, pgAdmin 4, etc).

* **T**ransform: what data cleaning or transformation was required.

* **L**oad: the final database, tables/collections, and why this was chosen.

Please upload the report to Github and submit a link to Bootcampspot.
