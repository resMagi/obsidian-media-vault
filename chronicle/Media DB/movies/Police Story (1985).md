---

gf: false
type: movie
subType: ""
title: Police Story
englishTitle: Police Story
year: "1985"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0089374/
id: tt0089374
plot: A virtuous Hong Kong Police Officer must clear his good name when the drug lord he is after frames him for the murder of a dirty cop.
genres:
  - Action
  - Comedy
  - Crime
director:
  - Jackie Chan
writer:
  - Jackie Chan
  - Edward Tang
studio:
  - N/A
duration: 100 min
onlineRating: 7.5
actors:
  - Jackie Chan
  - Maggie Cheung
  - Brigitte Lin
image: https://m.media-amazon.com/images/M/MV5BZTMxMWUxNjctOGNiOC00MzRkLWI1NjktZWUzOGJiZTM2ZDg1XkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 12-14-01985
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