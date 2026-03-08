---

gf: false
type: movie
subType: ""
title: Rumble in the Bronx
englishTitle: Rumble in the Bronx
year: "1995"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0113326/
id: tt0113326
plot: A young man visiting and helping his uncle in New York City finds himself forced to fight a street gang and the mob with his martial art skills.
genres:
  - Action
  - Comedy
  - Crime
director:
  - Stanley Tong
writer:
  - Edward Tang
  - Fibe Ma
studio:
  - N/A
duration: 87 min
onlineRating: 6.8
actors:
  - Jackie Chan
  - Anita Mui
  - Françoise Yip
image: https://m.media-amazon.com/images/M/MV5BNWUxMDcyZTMtYzJjMi00Y2Q1LWE3NWMtNTRiNGQxZTljYjE2XkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 02-23-01996
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