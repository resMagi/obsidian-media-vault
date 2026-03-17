---
gf: false
type: movie
subType: ""
title: Spirited Away
englishTitle: Spirited Away
year: "2001"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0245429/
id: tt0245429
plot: During her family's move to the suburbs, a sullen 10-year-old girl wanders into a world ruled by gods, witches and spirits, and where humans are changed into beasts.
genres:
  - Animation
  - Adventure
  - Family
director:
  - Hayao Miyazaki
writer:
  - Hayao Miyazaki
studio:
  - N/A
duration: 124 min
onlineRating: 8.6
actors:
  - Miyu Irino
  - Rumi Hiiragi
  - Mari Natsuki
image: https://m.media-amazon.com/images/M/MV5BNTEyNmEwOWUtYzkyOC00ZTQ4LTllZmUtMjk0Y2YwOGUzYjRiXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 03-28-02003
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