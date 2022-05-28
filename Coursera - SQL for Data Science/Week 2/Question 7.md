![Module-2-Coding-Assignment-Coursera (7)](https://user-images.githubusercontent.com/79485961/170844557-31656253-956c-4905-aeac-dc5477b469bb.png)

***Answer:***

```sql

Select InvoiceId
        , BillingCity
        , Total

From Invoices

where BillingCity in ( 'Brasília', 'Edmonton', 'Vancouver')

Order by InvoiceId Desc;

```
