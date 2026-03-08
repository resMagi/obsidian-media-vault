---

gf: false
type: movie
subType: ""
title: "Dr. Strangelove or: How I Learned to Stop Worrying and Love the Bomb"
englishTitle: "Dr. Strangelove or: How I Learned to Stop Worrying and Love the Bomb"
year: "1964"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0057012/
id: tt0057012
plot: A mentally unstable American general orders a hydrogen bomb attack on the Soviet Union, triggering a path to global nuclear holocaust that a war room full of politicians and generals frantically tries to stop.
genres:
  - Comedy
  - War
director:
  - Stanley Kubrick
writer:
  - Stanley Kubrick
  - Terry Southern
  - Peter George
studio:
  - N/A
duration: 95 min
onlineRating: 8.3
actors:
  - Peter Sellers
  - George C. Scott
  - Sterling Hayden
image: https://m.media-amazon.com/images/M/MV5BMjFjYzBlOTktMTI2OS00ZWVhLTgxMDUtNzAwODY2NmI3YTAzXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 01-29-01964
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