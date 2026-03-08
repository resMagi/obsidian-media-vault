---
gf: false
type: movie
subType: ""
title: Pulp Fiction
englishTitle: Pulp Fiction
year: "1994"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0110912/
id: tt0110912
plot: The lives of two mob hitmen, a boxer, a gangster and his wife, and a pair of diner bandits intertwine in four tales of violence and redemption.
genres:
  - Crime
  - Drama
director:
  - Quentin Tarantino
writer:
  - Quentin Tarantino
  - Roger Avary
studio:
  - N/A
duration: 154 min
onlineRating: 8.8
actors:
  - John Travolta
  - Uma Thurman
  - Samuel L. Jackson
image: https://m.media-amazon.com/images/M/MV5BYTViYTE3ZGQtNDBlMC00ZTAyLTkyODMtZGRiZDg0MjA2YThkXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 10-14-01994
watched: true
lastWatched: ""
personalRating: 9.5
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