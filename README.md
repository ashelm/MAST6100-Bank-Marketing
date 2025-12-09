# Bank-Marketing- Analysis
## Table of Contents
 - Project Overview
 - Data Sources
 - Field Description
 - Citation
 - Contributors

### Project Overview
The Bank Marketing dataset relates to direct marketing campaigns of a Portuguese bank insituition. The campaigns were conducted via phone calls, often requiring multiple contacts with the same client to determine whether they would subscribe to a term deposit. The goal of this project is to analyse the dataset to identify patterns and trends in client behaviour and develop predictive models to forecast whether a client is likely to subscribe to a term deposit based on their demographic and campaign related attributes.

## Data Source
The datase was created by Paulo Cortez (University of Minho) and Sergio Moro (ISCTE-IUL) in 2012. It is publicly available for research and can be found [here](https://archive.ics.uci.edu/dataset/222/bank+marketing).

There are two datasets: 
      1) bank-full.csv with all examples, ordered by date (from May 2008 to November 2010).
      2) bank.csv with 10% of the examples (4521), randomly selected from bank-full.csv.

The classification goal is to predict whether a client will subscribe to a term deposit (y).

## Field Description
### Input variables:
 ### Bank client data:
   1. age (numeric)
   2. job : type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student","blue-collar","self-employed","retired","technician","services") 
   3. marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
   4. education (categorical: "unknown","secondary","primary","tertiary")
   5. default: has credit in default? (binary: "yes","no")
   6. balance: average yearly balance, in euros (numeric) 
   7. housing: has housing loan? (binary: "yes","no")
   8. loan: has personal loan? (binary: "yes","no")
   
   ### Related with the last contact of the current campaign:
   9. contact: contact communication type (categorical: "unknown","telephone","cellular") 
  10. day: last contact day of the month (numeric)
  11. month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")
  12. duration: last contact duration, in seconds (numeric)
  
   ### Other attributes:
  13. campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
  14. pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)
  15. previous: number of contacts performed before this campaign and for this client (numeric)
  16.  poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")

  ### Output variable
  17. y - has the client subscribed a term deposit? (binary: "yes","no")

## Citation
Moro, S., Rita, P., & Cortez, P. (2014). Bank Marketing [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5K306.

## Contributors
  Ashel Munemo
   
  
