---
layout: post
title: "Web scrapping with python \n
[financial_Data]"
subtitle: "python code using BS4 and Selenium for web scrapping stock data"
background: '/img/posts/selenium.png.png'
---

## Web Scraping Financial Data from stockanalysis.com

### This project aims to extract financial data from the stockanalysis.com website using web scraping techniques. The extracted data can be used for financial analysis and modeling.

1) Installation
To install the required libraries, run:

pip install -r requirements.txt

2) Usage

To run the web scraper, run:

### main_stock_finantial.py:
in order to extract .xlsx file with datasets for each important aspect of the companie or stock that youre interested in. the Symbol variable is where you should put the convention, for example EC for Ecopetrol data.

This .xlsx file can then be read by eda_generator.py that automatically proceeds to create EDA jupyter notebook files for each sheet of the .xlsx file you just generated.

### scrapping_canvas.py:
 is a file that can extract important chat in PNG using the same symbol that you used in main_stock_finantial.  the EDA jupyter notebooks that are in this repository where created using eda_generator.py and implement sweetviz librarie for data analysis creating an HTML report for each excel file.

 [git_hub link to project repository](https://github.com/Al-goritmus/finantial_web_scrapping_python)

#### note: 
automatically generated EDA files are uploaded but can't be read as normally in Github because Colab and github use different
notation for the json metadata of the notebook, specifically Github uses:"execution_count": null  and Colab uses "execution_count": 'null',  but these files are meant to be used in colab, So, I'm just gonna leave one of the EDA's shared from colab in order for you to be able to watch the final product.

![EDA_generator_code](\img\posts\finance_project.png)

![EDA_generator_code](\img\posts\selenium.png.png)