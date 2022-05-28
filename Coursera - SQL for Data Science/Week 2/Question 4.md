![Module-2-Coding-Assignment-Coursera (4)](https://user-images.githubusercontent.com/79485961/170843194-20af0893-d2e4-4267-9636-b727b5209b41.png)

***Answer:***

```sql
Select CustomerId
        , InvoiceId
        , InvoiceDate
        , Total

From Invoices
where (CustomerId in ('56', '58')) and (Total between '1.00' and '5.00') 
```
