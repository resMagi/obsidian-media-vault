---
gf: false
type: movie
subType: ""
title: Eighth Grade
englishTitle: Eighth Grade
year: "2018"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt7014006/
id: tt7014006
plot: An introverted teenage girl tries to survive the last week of her disastrous eighth grade year before leaving to start high school.
genres:
  - Comedy
  - Drama
director:
  - Bo Burnham
writer:
  - Bo Burnham
studio:
  - N/A
duration: 93 min
onlineRating: 7.3
actors:
  - Elsie Fisher
  - Josh Hamilton
  - Emily Robinson
image: https://m.media-amazon.com/images/M/MV5BMTUyYzNiZTQtZGEwYi00ZjdiLTk5ZjctYTAxZTY3YmY0OThlXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 08-03-02018
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