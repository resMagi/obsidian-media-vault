---
gf: false
type: movie
subType: ""
title: "2001: A Space Odyssey"
englishTitle: "2001: A Space Odyssey"
year: "1968"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0062622/
id: tt0062622
plot: When a mysterious artifact is uncovered on the Moon, a spacecraft manned by two humans and one supercomputer is sent to Jupiter to find its origins.
genres:
  - Adventure
  - Sci-Fi
director:
  - Stanley Kubrick
writer:
  - Stanley Kubrick
  - Arthur C. Clarke
studio:
  - N/A
duration: 149 min
onlineRating: 8.3
actors:
  - Keir Dullea
  - Gary Lockwood
  - William Sylvester
image: https://m.media-amazon.com/images/M/MV5BNjU0NDFkMTQtZWY5OS00MmZhLTg3Y2QtZmJhMzMzMWYyYjc2XkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 05-12-01968
watched: true
lastWatched: ""
personalRating: 9
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