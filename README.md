# Pet Shelter Data Analysis Notebook

Demonstration of skills analyzing data from a pet shelter. The CSV data contains tables detailing incoming and outgoing animals and I use my knowledge of Pandas to gather and present the requested information.

This notebook was created using JupyterLab application through Anaconda. 

---

## Notebook Organization

The notebook is divided into the following sections. Note some sections aren't necessary to the analysis but included for completeness.

A. Setup and import data

B. Initial investigation of the data

* View the head() of each DataFrame
* View the info() of each DataFrame
* View the describe() output for each DataFrame
* View the length of each DataFrame
* View the shape() for each DataFrame
* View the dtypes() for each DataFrame

C. Clean the data and prepare it for analysis

* Handle Duplicates: Repeated data
* Combine the two DataFrames
* Handle Formatting: Misspellings, extra whitespace, differences after combining multiple datasets
* Handle Missing Data: Data labeled as unknown, Nan, or empty
* Handle Type Issues: Data that is a different type than expected
* Handle Nonsensical Data: Data that does not make sense
* Handle Saturated Data: Data that is at the extremes of the measurement
* Handle Confidential Data: Personally identifiable information
* Handle Individual Errors: Errors that affect a single value
* Handle Systematic Errors: Errors that affect all or large portions of the data
* Create Additional Columns for Analysis

D. Analyze the data

1. Is there an area where more pets are found?
2. What is the average number of pets found in a month in the year 2015? Are there months where there is a higher number of animals found?
3. What is the ratio of incoming pets vs. adopted pets?
4. What is the distribution of the types of animals in the shelter?
5. What are the adoption rates for specific breeds?
6. What are the adoption rates for different colorings?
7. About how many animals are spayed/neutered each month?

Additional Solutions for Exceeds Rating

1. How many animals in the shelter are repeats? Which animal was returned to the shelter the most?
2. What are the adoption rates for the following age groups?

* baby: 4 months and less
* young: 5 months - 2 years
* adult: 3 years - 10 years
* senior: 11+

3. If spay/neuter for a dog costs 100 dollars and a spay/neuter for a cat costs 50 dollars, how much did the shelter spend in 2015 on these procedures?

---

## Data

Source: <https://www.kaggle.com/datasets/aaronschlegel/austin-animal-center-shelter-intakes-and-outcomes>
