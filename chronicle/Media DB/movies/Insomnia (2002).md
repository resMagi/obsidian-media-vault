---

gf: false
type: movie
subType: ""
title: Insomnia
englishTitle: Insomnia
year: "2002"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0278504/
id: tt0278504
plot: A Los Angeles detective chases a murder suspect in a remote Alaskan town.
genres:
  - Drama
  - Mystery
  - Thriller
director:
  - Christopher Nolan
writer:
  - Hillary Seitz
  - Nikolaj Frobenius
  - Erik Skjoldbjærg
studio:
  - N/A
duration: 118 min
onlineRating: 7.2
actors:
  - Al Pacino
  - Robin Williams
  - Hilary Swank
image: https://m.media-amazon.com/images/M/MV5BOTE2NzQ0MzQtMDRmZi00ZWRiLWE4MDEtY2M1Mjc3OGY5N2JkXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 05-24-02002
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