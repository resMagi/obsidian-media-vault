---

gf: false
type: movie
subType: ""
title: "Twilight of the Warriors: Walled In"
englishTitle: "Twilight of the Warriors: Walled In"
year: "2024"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt20316748/
id: tt20316748
plot: Follows troubled youth Chan Lok-kwun as he accidentally enters the Walled City, discovers the order amidst its chaos, and learns important life lessons along the way.
genres:
  - Action
  - Crime
  - Thriller
director:
  - Soi Cheang
writer:
  - Kin-Yee Au
  - Tai-Lee Chan
  - Li Jun
studio:
  - N/A
duration: 126 min
onlineRating: 6.9
actors:
  - Louis Koo
  - Sammo Kam-Bo Hung
  - Richie Jen
image: https://m.media-amazon.com/images/M/MV5BYTIzODllOTItMmQ3ZC00Yzg0LTg3NjgtZjBiODNmYzViYTE0XkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 05-01-02024
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