---

gf: false
type: movie
subType: ""
title: Goodfellas
englishTitle: Goodfellas
year: "1990"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0099685/
id: tt0099685
plot: The story of Henry Hill and his life in the mafia, covering his relationship with his wife Karen and his mob partners Jimmy Conway and Tommy DeVito.
genres:
  - Biography
  - Crime
  - Drama
director:
  - Martin Scorsese
writer:
  - Nicholas Pileggi
  - Martin Scorsese
studio:
  - N/A
duration: 145 min
onlineRating: 8.7
actors:
  - Robert De Niro
  - Ray Liotta
  - Joe Pesci
image: https://m.media-amazon.com/images/M/MV5BN2E5NzI2ZGMtY2VjNi00YTRjLWI1MDUtZGY5OWU1MWJjZjRjXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 09-21-01990
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