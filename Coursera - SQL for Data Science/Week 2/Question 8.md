![Module-2-Coding-Assignment-Coursera (9)](https://user-images.githubusercontent.com/79485961/170845695-31c7c16a-62a8-460f-9696-97c0d1d9f14b.png)


***Answer:***

```sql

Select CustomerId
        ,count(InvoiceId) AS Orders
        , Total

From Invoices

group by CustomerId
order by Orders DESC;
```
