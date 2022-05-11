# Biomine Goals
- Incentivize people to share metabolomics & exposomics data to
  - Enable population-scale studies 
  - Enable post theory science
  - Enable personalized health
  - Build predictive models
- Create a data marketplace to 
  - Enable DeSci
- Screen metabolites of blue zone population to
  - **Find signatures responsible for longevity** 

More info: https://biomine.xyz/

# Specifications
- Mass spectrometry-based metabolomics data recorded in vendor-specific formats
- For exchangeability most often converted to XML schema-based format 
  - https://www.psidev.info/mzML
  - example_data/raw_14HM225.mzML
- Could also be represented as rows and columns in a relational database
- Metadata concerning individuals could be part of database 
  - Recorded personal information and surveys

## Storage
- Store database rows as encrypted distributed shards 

## Governance
- Data is recorded (anonymized) by lab 
- Only user can assemble shards back into a full data set 
- Researchers gain one-time access to the data if the user so chooses
  - Only able to access metadata they bargained for 
- Data sharing is easy and transparent

## Features
- Marketplace for data
- DAO can vote on research targets for Biomine research team
- Contributers (Bioneers) earn token for sharing data

# Tasks
- Learn about metabolomics (data)
- Flesh out a concept 