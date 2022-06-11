![Module-3-Coding-Assignment-Coursera (10)](https://user-images.githubusercontent.com/79485961/171996415-37f8c423-96ec-4720-a82d-60858b8761d2.png)

***Answer:***

```SQL
select customers.customerId
        , Lastname
        , city
        , BillingCity
From customers left join invoices
on customers.customerId = invoices.customerId
where city != BillingCity;

```
