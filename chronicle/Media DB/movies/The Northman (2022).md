---
gf: false
type: movie
subType: ""
title: The Northman
englishTitle: The Northman
year: "2022"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt11138512/
id: tt11138512
plot: A young Viking prince is on a quest to avenge his father's murder.
genres:
  - Action
  - Adventure
  - Drama
director:
  - Robert Eggers
writer:
  - Sjón
  - Robert Eggers
studio:
  - N/A
duration: 137 min
onlineRating: 7
actors:
  - Alexander Skarsgård
  - Nicole Kidman
  - Claes Bang
image: https://m.media-amazon.com/images/M/MV5BYzgwM2JiY2MtNWQ5OC00NDc1LWExMjYtYmY2YjViZmViYWM5XkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 04-22-02022
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