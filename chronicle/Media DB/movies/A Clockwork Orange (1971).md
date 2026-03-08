---

gf: false
type: movie
subType: ""
title: A Clockwork Orange
englishTitle: A Clockwork Orange
year: "1971"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0066921/
id: tt0066921
plot: Alex DeLarge and his droogs barbarize a decaying near-future.
genres:
  - Crime
  - Sci-Fi
director:
  - Stanley Kubrick
writer:
  - Stanley Kubrick
  - Anthony Burgess
studio:
  - N/A
duration: 136 min
onlineRating: 8.2
actors:
  - Malcolm McDowell
  - Patrick Magee
  - Michael Bates
image: https://m.media-amazon.com/images/M/MV5BMTY3MjM1Mzc4N15BMl5BanBnXkFtZTgwODM0NzAxMDE@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 02-02-01972
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