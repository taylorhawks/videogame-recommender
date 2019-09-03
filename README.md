# videogame-recommender

Collaborative filtering for videogame recommendations based on Steam playtime. Based on Australian gamers so there's lots of cricket and no Simpsons. 😮

### Some Notes
- The recommendation pipeline itself is in the pyspark notebook.
- I tried different binning techniques to try to address the weirdness of some of the recommendations, but it didn't really help.
- If anything the "weird" recommendations just go to show the importance of adding content-based filtering techniques.
- Note that this is all Australian data so they're biased toward cricket games.
