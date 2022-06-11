![Module-3-Coding-Assignment-Coursera (5)](https://user-images.githubusercontent.com/79485961/171996104-5a4704f1-852a-44c6-91fd-06f6edfb70e0.png)

***Answer:***

```SQL

Select TrackId
        , Name
        , Albums.AlbumId
        , Title
        , ArtistId
    From Albums Left Join Tracks on Albums.AlbumId = Tracks.AlbumId

    where Title = "For Those About To Rock We Salute You" ;

```
