---

gf: false
type: movie
subType: ""
title: The Godfather Part II
englishTitle: The Godfather Part II
year: "1974"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0071562/
id: tt0071562
plot: The early life and career of Vito Corleone in 1920s New York City is portrayed, while his son, Michael, expands and tightens his grip on the family crime syndicate.
genres:
  - Crime
  - Drama
director:
  - Francis Ford Coppola
writer:
  - Francis Ford Coppola
  - Mario Puzo
studio:
  - N/A
duration: 202 min
onlineRating: 9
actors:
  - Al Pacino
  - Robert De Niro
  - Robert Duvall
image: https://m.media-amazon.com/images/M/MV5BMDIxMzBlZDktZjMxNy00ZGI4LTgxNDEtYWRlNzRjMjJmOGQ1XkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 12-18-01974
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