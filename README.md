# Credit Risk Analysis

## Project Overview

Financial institutions face significant challenges in identifying loan applicants who are likely to default. Incorrect lending decisions can lead to substantial financial losses, while overly restrictive approvals may result in missed business opportunities.

This project performs Exploratory Data Analysis (EDA) on historical loan application data to identify the key factors associated with loan default. The insights generated can help financial institutions improve risk assessment and make more informed lending decisions.

---

## Business Objective

The objective of this project is to identify the driving factors behind loan default and determine the characteristics of high-risk and low-risk loan applicants.

The findings can be used to:

* Improve credit risk assessment
* Reduce loan defaults
* Enhance portfolio management
* Support data-driven lending decisions

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Data Preparation

### Data Cleaning

Several columns with more than 30% missing values were removed to improve data quality and analysis reliability.

### Missing Value Treatment

#### Numerical Variables

* Median imputation was used for highly skewed numerical features.

#### Categorical Variables

* Mode imputation was used for categorical features.

---

## Exploratory Data Analysis

### Univariate Analysis

The following borrower characteristics were analyzed:

* Gender
* Family Status
* Education Level
* Occupation Type
* Income Type
* Client Type

### Key Observations

* More than half of loan applicants were female.
* Married applicants constituted the largest borrower segment.
* Most applicants had secondary-level education.
* Labourers represented the largest occupational group.
* Working professionals accounted for the majority of applicants.
* Existing customers applied for loans more frequently than new customers.

---

## Bivariate Analysis

The relationship between borrower attributes and loan default was examined.

### Default Rate by Gender

| Gender | Default Rate |
| ------ | ------------ |
| Male   | 10.8%        |
| Female | 7.6%         |

**Insight:** Male applicants exhibited a higher probability of default.

### Default Rate by Income Type

High-risk categories:

* Maternity Leave (100%)
* Unemployed (54.5%)

Low-risk categories:

* Pensioners
* State Servants
* Commercial Associates

### Default Rate by Education

High-risk:

* Lower Secondary Education (10.9%)

Low-risk:

* Academic Degree (1.7%)
* Higher Education (6.1%)

### Default Rate by Family Status

Higher Risk:

* Civil Marriage
* Single / Not Married

Lower Risk:

* Widows

### Previous Loan Application Status

Higher Risk:

* Refused Applications
* Cancelled Applications

Lower Risk:

* Previously Approved Applications

---

## Multivariate Analysis

The project further explored interactions between multiple borrower characteristics.

### High-Risk Borrower Profiles

* Male applicants with lower secondary education
* Male applicants who are unmarried or in civil marriages
* Male applicants with previously refused loan applications
* Unemployed married applicants
* Applicants on maternity leave

### Low-Risk Borrower Profiles

* Female applicants with higher education
* Widows earning as state servants or commercial associates
* Applicants with previously approved loan applications

---

## Key Driver Variables of Loan Default

The analysis identified three major drivers of loan default:

### 1. Education Level

* Lower Secondary Education → Highest risk
* Higher Education and Academic Degrees → Lowest risk

### 2. Income Type

* Unemployed and Maternity Leave categories showed the highest default rates.
* State Servants, Pensioners, and Commercial Associates demonstrated lower risk.

### 3. Previous Loan Application Status

* Refused and Cancelled applications were associated with higher default rates.
* Approved applications were associated with lower default rates.

---

## Business Recommendations

* Implement stricter credit evaluation for applicants with lower educational qualifications.
* Increase scrutiny for unemployed applicants and those on maternity leave.
* Consider previous loan approval history as an important risk indicator.
* Offer preferential loan terms to applicants with strong repayment histories.
* Develop risk-based lending strategies using the identified driver variables.

---

## Conclusion

The analysis successfully identified the key factors influencing loan default behavior. Education level, income type, and previous application status emerged as the strongest indicators of credit risk. These insights can help financial institutions make more informed lending decisions and reduce overall portfolio risk.
