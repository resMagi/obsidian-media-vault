---

gf: false
type: movie
subType: ""
title: Eyes Wide Shut
englishTitle: Eyes Wide Shut
year: "1999"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0120663/
id: tt0120663
plot: A Manhattan doctor embarks on a bizarre, night-long odyssey after his wife's admission of unfulfilled longing.
genres:
  - Drama
  - Mystery
  - Thriller
director:
  - Stanley Kubrick
writer:
  - Stanley Kubrick
  - Frederic Raphael
  - Arthur Schnitzler
studio:
  - N/A
duration: 159 min
onlineRating: 7.5
actors:
  - Tom Cruise
  - Nicole Kidman
  - Todd Field
image: https://m.media-amazon.com/images/M/MV5BZTQ0MmM5MDAtYmYyZS00MzlmLTlhZTAtZDJlZWY5ZTZkZjZmXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 07-16-01999
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