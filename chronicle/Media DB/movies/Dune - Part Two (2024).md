---
gf: false
type: movie
subType: ""
title: "Dune: Part Two"
englishTitle: "Dune: Part Two"
year: "2024"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt15239678/
id: tt15239678
plot: Paul Atreides unites with the Fremen while on a warpath of revenge against the conspirators who destroyed his family. Facing a choice between the love of his life and the fate of the universe, he endeavors to prevent a terrible fu...
genres:
  - Action
  - Adventure
  - Drama
director:
  - Denis Villeneuve
writer:
  - Denis Villeneuve
  - Jon Spaihts
  - Frank Herbert
studio:
  - N/A
duration: 166 min
onlineRating: 8.4
actors:
  - Timothée Chalamet
  - Zendaya
  - Rebecca Ferguson
image: https://m.media-amazon.com/images/M/MV5BNTc0YmQxMjEtODI5MC00NjFiLTlkMWUtOGQ5NjFmYWUyZGJhXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 03-01-02024
watched: true
lastWatched: ""
personalRating: 9
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