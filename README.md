# Order automation for PrestaShop online store software

Automation of the ordering process in PrestShop online store software. 
Based on Selenium platform for automated testing of web applications in Python.

- There is no sample product and transaction database in the community that can be imported into a PrestaShop store, which would allow in-depth analysis of sales and logistics.
- The API query is very complicated and requires manual declaration of many parameters, which in the case of the actual order path are generated automatically. 

The automation takes into account the assumptions:
1. generates orders so that the average basket size is 1.5.
2. the popularity of products was determined by a normal distribution.
3. Adds products to the shopping cart according to the specified parameters,
4. Completes address and personal information and then generates an order. 
5. Requires to disable friendly URLs in the store settings.
The program was written for a master's thesis to fill a test store installed on localhost.  The master's thesis was entitled "Analytical system for online stores in the area of logistics management".
Implemented error handling, allowed to generate 13 thousand orders.
