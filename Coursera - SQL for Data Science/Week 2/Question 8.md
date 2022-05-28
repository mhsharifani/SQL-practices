![Module-2-Coding-Assignment-Coursera (8)](https://user-images.githubusercontent.com/79485961/170845448-3cffb845-c201-4e05-ac94-072a6fe5297e.png)

***Answer:***

```sql

Select CustomerId
        , InvoiceId
        ,count(InvoiceId) AS Orders
        , Total

From Invoices

group by CustomerId
order by Orders DESC;
```
