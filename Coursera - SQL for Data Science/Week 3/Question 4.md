![Module-3-Coding-Assignment-Coursera (6)](https://user-images.githubusercontent.com/79485961/171996193-cf331668-b3e7-44c5-b04f-33062cb45902.png)

***Answer:***

```SQL

Select   M.EmployeeId as MangerId
        , M.LastName as M_Lastname
        , E.ReportsTo as EM
        ,  E.LastName as E_Lastname
        , E.EmployeeId As EI
    

From Employees M Inner Join Employees E
on M.EmployeeId = E.ReportsTo

```
