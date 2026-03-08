---

gf: false
type: movie
subType: ""
title: Full Metal Jacket
englishTitle: Full Metal Jacket
year: "1987"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0093058/
id: tt0093058
plot: A pragmatic U.S. Marine observes the dehumanizing effects the Vietnam War has on his fellow recruits from their brutal boot camp training to the bloody street fighting in Hue.
genres:
  - Drama
  - War
director:
  - Stanley Kubrick
writer:
  - Stanley Kubrick
  - Michael Herr
  - Gustav Hasford
studio:
  - N/A
duration: 116 min
onlineRating: 8.2
actors:
  - Matthew Modine
  - R. Lee Ermey
  - Vincent D'Onofrio
image: https://m.media-amazon.com/images/M/MV5BYWUzNzZkNzUtNDdiYy00Nzk5LTgxMmItNTk0MjRjNjdjNDA0XkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 07-10-01987
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