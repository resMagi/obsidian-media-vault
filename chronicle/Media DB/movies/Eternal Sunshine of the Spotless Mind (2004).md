---
gf: true
type: movie
subType: ""
title: Eternal Sunshine of the Spotless Mind
englishTitle: Eternal Sunshine of the Spotless Mind
year: "2004"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0338013/
id: tt0338013
plot: When their relationship turns sour, a couple undergoes a medical procedure to have each other erased from their memories forever.
genres:
  - Drama
  - Romance
  - Sci-Fi
director:
  - Michel Gondry
writer:
  - Charlie Kaufman
  - Michel Gondry
  - Pierre Bismuth
studio:
  - N/A
duration: 108 min
onlineRating: 8.3
actors:
  - Jim Carrey
  - Kate Winslet
  - Tom Wilkinson
image: https://m.media-amazon.com/images/M/MV5BMTY4NzcwODg3Nl5BMl5BanBnXkFtZTcwNTEwOTMyMw@@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 03-19-02004
watched: false
lastWatched: ""
personalRating: 0
tags: mediaDB/tv/movie
---

`$= '![Image|360](' + dv.current().image + ')'`

  

# `$= dv.current().title`
  

**Genres**:

```dataviewjs

dv.current().genres.length === 0 ? dv.span(' - none') : dv.list(dv.current().genres)

```

  

```dataviewjs

if (!dv.current().released) {

dv.span('**Not released** The movie is not yet released.')

}

```

  

**Type**: `$= dv.current().type`

**Online Rating**: `$= dv.current().onlineRating`

**Duration**: `$= dv.current().duration`

**Premiered**: `$= dv.current().premiere`

**Producer**: `$= dv.current().producer`

---
## Review

## Notes