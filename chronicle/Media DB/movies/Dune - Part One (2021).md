---
gf: false
type: movie
subType: ""
title: "Dune: Part One"
englishTitle: "Dune: Part One"
year: "2021"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt1160419/
id: tt1160419
plot: Paul Atreides arrives on Arrakis after his father accepts the stewardship of the dangerous planet. However, chaos ensues after a betrayal as forces clash to control melange, a precious resource.
genres:
  - Action
  - Adventure
  - Drama
director:
  - Denis Villeneuve
writer:
  - Jon Spaihts
  - Denis Villeneuve
  - Eric Roth
studio:
  - N/A
duration: 155 min
onlineRating: 8
actors:
  - Timothée Chalamet
  - Rebecca Ferguson
  - Zendaya
image: https://m.media-amazon.com/images/M/MV5BNWIyNmU5MGYtZDZmNi00ZjAwLWJlYjgtZTc0ZGIxMDE4ZGYwXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 10-22-02021
watched: true
lastWatched: ""
personalRating: 8
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