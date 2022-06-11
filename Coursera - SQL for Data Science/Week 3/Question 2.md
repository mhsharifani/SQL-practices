![Module-3-Coding-Assignment-Coursera (4)](https://user-images.githubusercontent.com/79485961/171996019-073b2dfe-a855-4da2-b1ab-bf724207542b.png)

***Answer:***

```SQL

Select Customers.CustomerId
        , FirstName
        , LastName
        , City
        , email
        , count(InvoiceId) As Total_Invoices
From Customers Left Join Invoices 
on Customers.CustomerId = Invoices.CustomerId
group by Customers.CustomerId;

```
