---

gf: false
type: movie
subType: ""
title: Sinners
englishTitle: Sinners
year: "2025"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt31193180/
id: tt31193180
plot: Trying to leave their troubled lives behind, twin brothers return to their hometown to start again, only to discover that an even greater evil is waiting to welcome them back.
genres:
  - Action
  - Drama
  - Horror
director:
  - Ryan Coogler
writer:
  - Ryan Coogler
studio:
  - N/A
duration: 137 min
onlineRating: 7.5
actors:
  - Michael B. Jordan
  - Jack O'Connell
  - Hailee Steinfeld
image: https://m.media-amazon.com/images/M/MV5BNjIwZWY4ZDEtMmIxZS00NDA4LTg4ZGMtMzUwZTYyNzgxMzk5XkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 04-18-02025
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