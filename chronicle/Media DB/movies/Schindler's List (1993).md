---

gf: false
type: movie
subType: ""
title: Schindler's List
englishTitle: Schindler's List
year: "1993"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0108052/
id: tt0108052
plot: In German-occupied Poland during World War II, industrialist Oskar Schindler gradually becomes concerned for his Jewish workforce after witnessing their persecution by the Nazis.
genres:
  - Biography
  - Drama
  - History
director:
  - Steven Spielberg
writer:
  - Thomas Keneally
  - Steven Zaillian
studio:
  - N/A
duration: 195 min
onlineRating: 9
actors:
  - Liam Neeson
  - Ralph Fiennes
  - Ben Kingsley
image: https://m.media-amazon.com/images/M/MV5BNjM1ZDQxYWUtMzQyZS00MTE1LWJmZGYtNGUyNTdlYjM3ZmVmXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 02-04-01994
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