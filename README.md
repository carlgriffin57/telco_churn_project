
# Telco churn project

### Carl Griffin
### June 2021

## Project description and Goals

This project will use data from a telco company and come up with a best-fit model to predict churn among the customers.

## Data Dictionary

| Attribute                | Definition                                                           | Data Type |
|--------------------------|----------------------------------------------------------------------|-----------|
| payment_type_id          | Indicates how a customer pays their bill each month                  | int64     |
| internet_service_type_id | Indicates what type of internet service a customer has               | int64     |
| contract_type_id         | Indicates which contract type a customer has                         | int64     |
| customer_id              | Alpha-numeric ID that identifies each customer                       | object    |
| gender                   | Gender of the customer                                               | object    |
| senior_citizen           | Indicates if the customer is 65 or older                             | int64     |
| partner                  | If a customer is married                                             | object    |
| dependents               | Indicates if a customer lives with dependents                        | object    |
| tenure                   | The length of a customers relationship with Telco measured in months | int64     |
| phone_service            | If a customer has phone service                                      | object    |
| multiple_lines           | If a customer has multiple phone lines                               | object    |
| online_security          | Indicates if a customer has online security add-on                   | object    |
| online_backup            | Indicates if a customer has online backups add-on                    | object    |
| device_protection        | Indicates if a customer has a protection plan for Telco devices      | object    |
| tech_support             | Indicates whether a customer has technical support add-on            | object    |
| streaming_tv             | Indicates if a customer uses internet to stream tv                   | object    |
| streaming_movies         | Indicates if a customer uses internet to stream movies               | object    |
| paperless_billing        | Indicates if a customer is enrolled in paperless billing             | object    |
| monthly_charges          | The amount a customer pays each month for services with Telco        | object    |
| total_charges            | The total amount a customer has paid for Telco services              | object    |
| churn                    | Indicates whether a customer has terminated service                  | object    |
| contract_type            | The type of contract a customer has                                  | object    |
| internet_service_type    | Indicates the type of internet service a customer has                | object    |
| payment_type             | How a customer pays their bill each month                            | object    |


## Project Planning

1.  Pull in the telco data
2.  Investigate the data to postulate drivers of churn
3.  Hypothesize the drivers of churn
4.  Determine irrevelant data and drop that data
5.  Clean the data by converting into numerical values
6.  Split the data into train, validate and test
7.  Run several models
8.  Determine best model
9.  Run that model on the test data
10. Reformat the data into a csv file showing who's likely to churn or not churn

## Initial Ideas

Check to see if month-to-month vs contracts causes churn.

Check to see if senior citizens vs non-senior citizens causes churn.

## Instructions for recreating project

Using Jupyter notebook:

Have an env.py file containing your hostname, username and password

Grab the acquire.py and prepare.py files

Execute the telco_churn_final.ipynb file
