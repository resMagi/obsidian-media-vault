---
gf: false
type: movie
subType: ""
title: Nosferatu
englishTitle: Nosferatu
year: "2024"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt5040012/
id: tt5040012
plot: A gothic tale of obsession between a haunted young woman and the terrifying vampire infatuated with her, causing untold horror in its wake.
genres:
  - Fantasy
  - Horror
  - Mystery
director:
  - Robert Eggers
writer:
  - Robert Eggers
  - Henrik Galeen
  - Bram Stoker
studio:
  - N/A
duration: 132 min
onlineRating: 7.1
actors:
  - Lily-Rose Depp
  - Nicholas Hoult
  - Bill Skarsgård
image: https://m.media-amazon.com/images/M/MV5BY2FhZGE3NmEtNWJjOC00NDI1LWFhMTQtMjcxNmQzZmEwNGIzXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 12-25-02024
watched: true
lastWatched: ""
personalRating: 10
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