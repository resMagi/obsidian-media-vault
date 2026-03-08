---
gf: true
type: movie
subType: ""
title: Mother
englishTitle: Mother
year: "2009"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt1216496/
id: tt1216496
plot: A mother desperately searches for the killer who framed her son for a girl's horrific murder.
genres:
  - Crime
  - Drama
  - Mystery
director:
  - Bong Joon Ho
writer:
  - Bong Joon Ho
  - Park Eun-kyo
studio:
  - N/A
duration: 129 min
onlineRating: 7.7
actors:
  - Kim Hye-ja
  - Won Bin
  - Jin Goo
image: https://m.media-amazon.com/images/M/MV5BMTQzMTg0NDA1M15BMl5BanBnXkFtZTgwODUzMTE0MjE@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 05-28-02009
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