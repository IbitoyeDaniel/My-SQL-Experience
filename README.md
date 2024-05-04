# My-SQL-Experience
Here, you get to find out somethings I know about SQL and how I query databases. I will be using Adventure works database to document this journey

### Question 1: Retrieve all columns from the Product table:
Answer:
```
Select *
from DimProduct

```
### Question 2: Retrieve the names of all products and their list prices

```
select Englishproductname, listprice
from DimProduct
```
### Question 3:Count the total number of products in the Product table:
```
select count(*) as Totalproducts
from DimProduct
```
### Question 4: Retrieve product names that contain the word "Mountain" in their name
```
SELECT EnglishProductName 
FROM dimProduct 
WHERE englishproductname 
LIKE '%Mountain%'
```
### Question 5: Retrieve all products with a list price greater than $100:
```
SELECT * 
FROM DimProduct 
WHERE ListPrice > 100;
```











