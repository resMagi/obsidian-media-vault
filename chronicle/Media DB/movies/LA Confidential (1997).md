---

gf: false
type: movie
subType: ""
title: L.A. Confidential
englishTitle: L.A. Confidential
year: "1997"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0119488/
id: tt0119488
plot: As corruption grows in 1950s Los Angeles, three policemen - one strait-laced, one brutal, and one sleazy - investigate a series of murders with their own brand of justice.
genres:
  - Crime
  - Drama
  - Mystery
director:
  - Curtis Hanson
writer:
  - James Ellroy
  - Brian Helgeland
  - Curtis Hanson
studio:
  - N/A
duration: 138 min
onlineRating: 8.2
actors:
  - Kevin Spacey
  - Russell Crowe
  - Guy Pearce
image: https://m.media-amazon.com/images/M/MV5BODdiMjY1OGYtNDk0NC00NGQ1LWI4MDItOTJhMTM0YjE1YTAzXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 09-19-01997
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