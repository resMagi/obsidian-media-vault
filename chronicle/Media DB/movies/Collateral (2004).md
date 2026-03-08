---
gf: false
type: movie
subType: ""
title: Collateral
englishTitle: Collateral
year: "2004"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0369339/
id: tt0369339
plot: A cab driver finds himself the hostage of an engaging contract killer as he makes his rounds from hit to hit during one night in Los Angeles.
genres:
  - Action
  - Crime
  - Drama
director:
  - Michael Mann
writer:
  - Stuart Beattie
studio:
  - N/A
duration: 120 min
onlineRating: 7.5
actors:
  - Tom Cruise
  - Jamie Foxx
  - Jada Pinkett Smith
image: https://m.media-amazon.com/images/M/MV5BMjE3NjM5OTMxMV5BMl5BanBnXkFtZTcwOTIzMTQyMw@@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 08-06-02004
watched: true
lastWatched: ""
personalRating: 7
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