# Programming For Data Science - Final Project

## 1. Introduction
--- (Hà ghi chỗ này nha)

### _1.0. Group members_

| Name              | ID       |
|-------------------|----------|
| Pham Dang Son Ha  | 21127206 |
| Nguyen Cao Khoi   | 21127632 |

### _1.1. Table of Contents_

1. [Introduction](#1.-Introduction)

2. [Collecting Data](#2.-Collecting-Data)

3. [Exploring And Preprocessing Data](#3.-Exploring-And-Preprocessing-Data)

4. [Asking Meaningful Questions And Analyzing](#4-Asking-Meaningful-Questions-And-Analyzing)

### _1.2. Link tasks assingment_

Link tasks assingment: https://docs.google.com/spreadsheets/d/16Zr87G9Je7Rl3tS1-R6aUrOBCYf_oEGRk8dgMuEUc-Q/edit?usp=sharing

## 2. Collecting Data

### _2.1. Subject And Source_

-  Subject: The [Online Retails Sale Dataset](https://www.kaggle.com/datasets/rohitmahulkar/online-retails-sale-dataset/data?fbclid=IwAR073q0CYe_aoD5bjPNrycjMGsDoXCxytfm8p7WpWJTBH9XkqrOCrbV_LRU) contains transactions from 12/01/2010 to 12/09/2011 of an online retail company based in the UK. It includes 10 attributes, and the number of rows in the dataset is 541,909 rows.

- Source: The author got this data from [Tata Data Visualisation: Empowering Business with Effective Insights](https://www.theforage.com/simulations/tata/data-visualisation-p5xo), which is a virtual internship program offered by Tata Insights and Quants (Tata iQ) on the Forage platform.

### _2.2. Authors And Copyright_

- Author: [Rohit Mahulkar](https://www.kaggle.com/rohitmahulkar) (Owner)

- Copyright: [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/) - This means others can freely use, modify, and build upon these works for any purpose without any restrictions.

## 3. Exploring Data

- There are 541909 rows and 10 columns.

- The meaning of each row: a transactions of an online retail company based in the UK. 

- There are 5268 duplicated rows and we will remove duplicated rows and keep only the first occurence

- The meaning of each column: 
    - `InvoiceNo`: Transactions ID for successfull orders
    - `InvoiceDate`: Date in which the orders place
    - `InvoiceTime`: Time stamp in which the orders place relevant to geoghraphical location
    - `StockCode`: Products ID
    - `Description`: Name of product (contain some missing names of products which are return, damaged, lost etc...)
    - `Quantity`: The quantity of products sold (contain negative number of quantity which are return,damageded, lost etc...)
    - `UnitPrice`: Selling price of a single unit of product
    - `Totalsale`: Total of selling price. (`Totalsale` = `UnitPrice` * `Quantity`)
    - `CustomerID`: Customer Id
    - `Country`: Country Name

## 4. Asking Meaningful Questions 

### _4.1. Which `Description` has the highest `Totalsale` value in a year?_

### _4.2. Which `Customer` buy the most ?_

### _4.3. How does the quantity of orders sold vary during certain times of the year?_

### _4.4. Which items are frequently bought together?_