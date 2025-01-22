# Project Name

LendingClub Case Study

## Table of Contents

* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

* What is the background of your project?
  > The background of this project is to develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.

* What is the business probem that your project is trying to solve?
  > The Business Problem that this project aims to solve is how consumer attributes and loan attributes influence the tendency of default and to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

* What is the dataset that is being used?
  > we are using a dataset of the complete loan data for all loans issued through the time period 2007 to 2011 by LendingClub - a consumer finance company which specialises in lending various types of loans to urban customers.

## Conclusions

* `grade`: Grade B has a relatively higher default rate.
* `sub_grade`: among the grades, we see that sub_grade B5 has a high default rate.
* `emp_length`: we can see loan applicants with 10+ years of experience are the highest defaulters.
* `home_ownership`: we can see loan applicants living in rented/mortgage house are the highest defaulters.
* `verification_status`: we can see loan applicants who are 'not verified' are the highest defaulters.
* `purpose`: we can see loan applicants whose loan purpose is related to 'debt_consolidation' are the highest defaulters.
* `loan_amnt`, `funded_amnt`, `funded_amnt_inv` & `installment` are highly correlated with `total_pymnt`, `total_pymnt_inv`, `total_rec_prncp`, `total_rec_int`.
* `total_acc` is highly correlated with `open_acc`.
* `pub_rec` is highly correlated with `pub_rec_bankruptcies`.

## Technologies Used

* `numpy`      - version 2.2.1
* `pandas`     - version 2.2.3
* `matplotlib` - version 3.10.0
* `seaborn`    - version 0.13.2
* `missingno`  - version 0.5.2
* `jupyter`    - version 1.1.1
* `python`     - version 3.13.0

## Acknowledgements

* This project was based on [this case study](https://learn.upgrad.com/course/7715/segment/53501/317620/962115/4806808).

## Contact

Created by [@ppauljonathan](https://github.com/ppauljonathan/) [@pradeepkumarr355199](https://github.com/pradeepkumarr355199) - feel free to contact us!
