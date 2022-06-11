![Module-3-Coding-Assignment-Coursera (9)](https://user-images.githubusercontent.com/79485961/171996380-fe210ee7-5117-488f-97c2-029532fe733d.png)

***Answer:***

```SQL
Select FirstName
        , Lastname
From Employees

Union 

Select FirstName
        , Lastname
From Customers

Order by Lastname DESC;

```
