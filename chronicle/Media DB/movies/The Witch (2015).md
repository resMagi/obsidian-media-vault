---
gf: false
type: movie
subType: ""
title: The Witch
englishTitle: The Witch
year: "2015"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt4263482/
id: tt4263482
plot: An isolated Puritan family in 1630s New England comes unraveled by the forces of witchcraft and possession.
genres:
  - Drama
  - Fantasy
  - Horror
director:
  - Robert Eggers
writer:
  - Robert Eggers
studio:
  - N/A
duration: 92 min
onlineRating: 7
actors:
  - Anya Taylor-Joy
  - Ralph Ineson
  - Kate Dickie
image: https://m.media-amazon.com/images/M/MV5BMTUyNzkwMzAxOF5BMl5BanBnXkFtZTgwMzc1OTk1NjE@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 02-19-02016
watched: true
lastWatched: ""
personalRating: 10
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