![Module-3-Coding-Assignment-Coursera (8)](https://user-images.githubusercontent.com/79485961/171996291-7749049d-bd76-4fb7-958c-04fc59b7dcb0.png)

***Answer:***

```SQL

Select Artists.ArtistId
        , Name
        , AlbumId
        , title

From Artists left join Albums
on Artists.ArtistId = Albums.ArtistId
where AlbumId is null

```
