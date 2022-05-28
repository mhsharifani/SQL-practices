![Module-2-Coding-Assignment-Coursera (3)](https://user-images.githubusercontent.com/79485961/170842719-0704db7c-3baf-42d4-90b6-7aca266b92fe.png)

***Answer:***

```sql
Select CustomerId
        , FirstName
        , LastName
        , Company
        , State

From Customers

Where State in ( 'RJ', 'DF', 'AB', 'BC', 'CA', 'WA', 'NY')

Order by State;


```
