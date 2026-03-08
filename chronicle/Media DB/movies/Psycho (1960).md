---

gf: false
type: movie
subType: ""
title: Psycho
englishTitle: Psycho
year: "1960"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0054215/
id: tt0054215
plot: A secretary on the run for embezzlement takes refuge at a secluded California motel owned by a repressed man and his overbearing mother.
genres:
  - Drama
  - Horror
  - Mystery
director:
  - Alfred Hitchcock
writer:
  - Joseph Stefano
  - Robert Bloch
studio:
  - N/A
duration: 109 min
onlineRating: 8.5
actors:
  - Anthony Perkins
  - Janet Leigh
  - Vera Miles
image: https://m.media-amazon.com/images/M/MV5BYjZhMzFiZjItODA3ZC00MmRhLWIzMGYtMmVjOWUwYTA3MTRjXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 09-08-01960
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