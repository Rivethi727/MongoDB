**1.Create a Database called movies.**
```
use movie

swiched to db movie
```
**2. Create a collection called moviedetails.**
```
db.createCollection("moviedetails")

{ ok: 1 }
```
**3.Create above 5 movie documents into a moviedetails collection.**
```
db.moviedetails.insertMany([{"Movie-Title":"Jurassic Park","Type":"Adventure","Director":"Steven spielberg","Release Year":1993},{"Movie-Title":"Forrest Gump","Type":"Drama","Director":"Robert Zemeckies","Release Year":1994},{"Movie-Title":"Titanic","Type":"Romance","Director":"James Cameron","Release Year":1997},{"Movie-Tittle":"The Dark knight","Type":"Action","Director":"Christopher Nolan","Release Year":2008},{"Movie-Title":"Avatar","Type":"Science Fiction","Director":"James Cameron","Release Year":2009}])

{
  acknowledged: true,
  insertedIds: {
    '0': ObjectId("654d14407d07c6266d5d94fc"),
    '1': ObjectId("654d14407d07c6266d5d94fd"),
    '2': ObjectId("654d14407d07c6266d5d94fe"),
    '3': ObjectId("654d14407d07c6266d5d94ff"),
    '4': ObjectId("654d14407d07c6266d5d9500")
  }
}
```







