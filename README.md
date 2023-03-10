# Deep Learning
## Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. This project aims to use machine learning and neural networks to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organisations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organisation, such as:

- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organisation classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organisation type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special considerations for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively
## Directory
**Starter_code** notebook preprocesses the data from charity_data.csv and creates five neural network models which aim to classify applicants as successful or unsuccessful.

**AlphabetSoupCharity_Optimisation** notebook preprocesses the data slightly further and tests the same five model with this data.

**Mod21_Report** summarises the Project steps and outcomes.

**AlphabetSoupCharity.h5** is the first model created. All other models have their weights saved only in the corresponding folders (model01, model01pp, etc.).

**Resources folder** contains the original data source _charity_data.csv_ and a preprocessed version _pp_charity_data.csv_ .

## References
IRS. Tax Exempt Organization Search Bulk Data Downloads. https://www.irs.gov/
