---
gf: false
type: movie
subType: ""
title: Shaun of the Dead
englishTitle: Shaun of the Dead
year: "2004"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0365748/
id: tt0365748
plot: The uneventful, aimless lives of a London electronics salesman and his layabout roommate are disrupted by the zombie apocalypse.
genres:
  - Comedy
  - Horror
director:
  - Edgar Wright
writer:
  - Simon Pegg
  - Edgar Wright
studio:
  - N/A
duration: 99 min
onlineRating: 7.8
actors:
  - Simon Pegg
  - Kate Ashfield
  - Nick Frost
image: https://m.media-amazon.com/images/M/MV5BNzNjZGE4YTUtOWU3OC00Mzg2LThjNWItMzUwYzEwMDgxYmVjXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 09-24-02004
watched: true
lastWatched: ""
personalRating: 10
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