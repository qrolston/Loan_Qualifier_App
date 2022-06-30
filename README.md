# Loan Qualifier Application

Loan Qualifier Application (stored as **app.py**) is a multi-function application to help users determine their qualification for a personal loan. 

The user has the ability to *import their own loan data csv file*- and then the app can filter through the loans using information provided by the customer (credit score, debt, income, loan amount and home value) to find the best suited loans for our user. Saving the user time and energy. 

The customer will also have the option to save their results to a CSV making it easier to communicate with lenders and organize their finance options.


---

## Technologies

**app.py** is a python based application. It leverages python 3.7 with the following packages:

* fire - For the command line interface,
* questionary - For interactive user prompts and dialogs 
    * python 3.9 uses may need to enter *'winpty'* in order to properly runthe questionary package

---

## Installation Guide

Before running the application first install the following dependencies

```python
pip install fire
pip install questionary
```

---

## Usage

To use the Loan Qualifier Application (**app.py**) user will have to have an exact path to provide in the CLI:
![screenshot of the terminal showing a prompt for cvs path and then cvs path pasted in](https://github.com/qrolston/Loan_Qualifier_App/blob/f89997b72415e4234f0fba06a9a38809f8e6f623/1.png)

### User will then be prompted to input their credit/finance information 
![screenshot of the terminal displaying questionary prompts for users personal information]https://github.com/qrolston/Loan_Qualifier_App/blob/f89997b72415e4234f0fba06a9a38809f8e6f623/2.png)

**app.py** will send back qualifying loans and ask user if they would like to save to CSV. If user marks 'Yes' then a CSV will be written to the path folder. If user marks 'No' then application will exit.
---

## Contributors

*Brought to you by Quianna Rolston*
> * [Email @ Quianna](quiannarolston@gmail.com)

> * [LinkedIn](https://www.linkedin.com/in/quianna-rolston/)

---

## License

UC Berkeley - FinTech Bootcamp '22


