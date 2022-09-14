# Financial Planning Tools
The project entails building a tool to help credit union members evaluate their financial health. Specifically, the credit union board wants the members to be able to do two things. First, they should be able to assess their monthly budgets. Second, they should be able to forecast a reasonably effective retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds.

Where it is evaluated the value of a prototype clients crypto wallet and current stock and bond portfolio to determine if the client has enough money in their emergency fund.

Also, to help determine whether the prototype client will have enough money to retire from their current investments in 30 years with a 60/40 portfolio split and in 10 years with an 80/20 we use Monte Carlo simulations.

Below we can check the plotted results.

![MC Stimulation Histogram](Images/5-4-monte-carlo-histogram.png)  |  ![MC Stimulation Overlay](Images/5-4-monte-carlo-line-plot.png)

---

## Technologies

This project was developed with python 3.7 with the following packages:

* [pandas](https://github.com/pandas-dev/pandas) - Providing fast, flexible, and expressive data structures designed to make working with "relational" or "labeled" data both easy and intuitive.

* [alpaca](https://github.com/alpacahq/alpaca-trade-api-python) - is a python library for the Alpaca Commission Free Trading API. It allows rapid trading algo development easily, with support for both REST and streaming data interfaces.

* [matplotlib](https://github.com/matplotlib/matplotlib)- Is a comprehensive library for creating static, animated, and interactive visualizations in Python. Matplotlib makes easy things easy and hard things possible.

* [JSON](https://www.json.org/json-en.html) -  is a lightweight data-interchange format. It is easy for humans to read and write.

* [dotenv](https://pypi.org/project/python-dotenv/) -  Python-dotenv reads key-value pairs from a .env file and can set them as environment variables. It helps in the development of applications following the 12-factor principles.

And as well I used [Jupyter Lab](https://github.com/jupyter/notebook) notebook to develope it.

---

## Installation Guide

Before running the application it is necessary to install the following dependencies.

* pandas
```conda install pandas``` 
* matplotlib
```conda install matplotlib```
* Jupyter Notebook
```pip install notebook```
* alpaca
```pip3 install alpaca-trade-api```
* dotenv
```pip install python-dotenv```

---
## Usage

To use the application you will need to clone the repo into your machine, navigate on terminal into it and open your [Jupyter Lab](https://github.com/jupyter/notebook) to run the file **financial_planning_tools.ipynb**. 


---

## Contributors

This was a project developed as a group during a Fintech Bootcamp hosted by UC Berkley Extension. 

---

## License
MIT



HAPPY CODING :) 
