---
gf: true
type: movie
subType: ""
title: Wolfwalkers
englishTitle: Wolfwalkers
year: "2020"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt5198068/
id: tt5198068
plot: A young apprentice hunter and her father journey to Ireland to help wipe out the last wolf pack. But everything changes when she befriends a free-spirited girl from a mysterious tribe rumored to transform into wolves by night.
genres:
  - Animation
  - Action
  - Adventure
director:
  - Tomm Moore
  - Ross Stewart
writer:
  - Will Collins
  - Tomm Moore
  - Ross Stewart
studio:
  - N/A
duration: 103 min
onlineRating: 8
actors:
  - Honor Kneafsey
  - Eva Whittaker
  - Sean Bean
image: https://m.media-amazon.com/images/M/MV5BYzg3MjBkYmYtZjZkZS00YWVkLTk3YjMtNDBlMTVmNDZkZDJhXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 11-13-02020
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