---
gf: false
type: movie
subType: ""
title: The Shining
englishTitle: The Shining
year: "1980"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0081505/
id: tt0081505
plot: A family heads to an isolated hotel for the winter, where a sinister presence influences the father into violence. At the same time, his psychic son sees horrifying forebodings from both the past and the future.
genres:
  - Drama
  - Horror
director:
  - Stanley Kubrick
writer:
  - Stephen King
  - Stanley Kubrick
  - Diane Johnson
studio:
  - N/A
duration: 146 min
onlineRating: 8.4
actors:
  - Jack Nicholson
  - Shelley Duvall
  - Danny Lloyd
image: https://m.media-amazon.com/images/M/MV5BNmM5ZThhY2ItOGRjOS00NzZiLWEwYTItNDgyMjFkOTgxMmRiXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 06-13-01980
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