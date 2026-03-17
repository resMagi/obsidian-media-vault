---
gf: false
type: movie
subType: ""
title: Alien
englishTitle: Alien
year: "1979"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0078748/
id: tt0078748
plot: After investigating a mysterious transmission of unknown origin, the crew of a commercial spacecraft encounters a deadly lifeform.
genres:
  - Horror
  - Sci-Fi
director:
  - Ridley Scott
writer:
  - Dan O'Bannon
  - Ronald Shusett
studio:
  - N/A
duration: 117 min
onlineRating: 8.5
actors:
  - Sigourney Weaver
  - Tom Skerritt
  - John Hurt
image: https://m.media-amazon.com/images/M/MV5BN2NhMDk2MmEtZDQzOC00MmY5LThhYzAtMDdjZGFjOGZjMjdjXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 06-22-01979
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