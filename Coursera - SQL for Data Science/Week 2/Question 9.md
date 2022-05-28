![Module-2-Coding-Assignment-Coursera (10)](https://user-images.githubusercontent.com/79485961/170845737-4e2455d6-eb15-45c3-ad6f-99930bb02c51.png)

***Answer:***

```sql

Select AlbumId
        , Count(TrackId) As Total_Tracks

From Tracks
Group by AlbumId
Having Total_Tracks > 12
order by Total_Tracks ASC; 

```
