---
gf: false
type: movie
subType: ""
title: Drunken Master
englishTitle: Drunken Master
year: "1978"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0080179/
id: tt0080179
plot: Wong Fei-Hung is a mischievous, yet righteous young man, but after a series of incidents, his frustrated father has him disciplined by a master of drunken martial arts.
genres:
  - Action
  - Comedy
director:
  - Yuen Woo-Ping
writer:
  - Lung Hsiao
  - See-Yuen Ng
studio:
  - N/A
duration: 111 min
onlineRating: 7.4
actors:
  - Jackie Chan
  - Siu-Tin Yuen
  - Jeong-lee Hwang
image: https://m.media-amazon.com/images/M/MV5BMGVjNzA2Y2QtNzNlOC00ODE2LWE3NDEtMzE4NzUwNjdhZWQzXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 10-05-01978
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