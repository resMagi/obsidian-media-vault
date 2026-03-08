---
gf: false
type: movie
subType: ""
title: Paddington
englishTitle: Paddington
year: "2014"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt1109624/
id: tt1109624
plot: A young Peruvian bear travels to London in search of a home. Finding himself lost and alone at Paddington Station, he meets the kindly Brown family, who offer him a temporary haven.
genres:
  - Adventure
  - Comedy
  - Family
director:
  - Paul King
writer:
  - Paul King
  - Hamish McColl
  - Michael Bond
studio:
  - N/A
duration: 95 min
onlineRating: 7.3
actors:
  - Tim Downie
  - Madeleine Worrall
  - Lottie Steer
image: https://m.media-amazon.com/images/M/MV5BMTAxOTMwOTkwNDZeQTJeQWpwZ15BbWU4MDEyMTI1NjMx._V1_SX300.jpg
released: true
streamingServices: []
premiere: 01-16-02015
watched: true
lastWatched: ""
personalRating: 8.5
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