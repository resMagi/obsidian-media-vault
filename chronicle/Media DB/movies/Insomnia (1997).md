---

gf: false
type: movie
subType: ""
title: Insomnia
englishTitle: Insomnia
year: "1997"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0119375/
id: tt0119375
plot: In a Norwegian city with a 24-hour daylight cycle, Swedish detectives investigate a teen's death.
genres:
  - Crime
  - Mystery
  - Thriller
director:
  - Erik Skjoldbjærg
writer:
  - Nikolaj Frobenius
  - Erik Skjoldbjærg
studio:
  - N/A
duration: 96 min
onlineRating: 7.2
actors:
  - Stellan Skarsgård
  - Sverre Anker Ousdal
  - Maria Mathiesen
image: https://m.media-amazon.com/images/M/MV5BMTQ3NDM1NjgxMF5BMl5BanBnXkFtZTgwOTM5NTY2MDE@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 05-29-01998
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