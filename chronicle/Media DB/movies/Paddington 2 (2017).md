---
gf: true
type: movie
subType: ""
title: Paddington 2
englishTitle: Paddington 2
year: "2017"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt4468740/
id: tt4468740
plot: Paddington, now happily settled with the Brown family and a popular member of the local community, picks up a series of odd jobs to buy the perfect present for his Aunt Lucy's 100th birthday, only for the gift to be stolen.
genres:
  - Adventure
  - Comedy
  - Family
director:
  - Paul King
writer:
  - Paul King
  - Simon Farnaby
  - Michael Bond
studio:
  - N/A
duration: 103 min
onlineRating: 7.8
actors:
  - Ben Whishaw
  - Hugh Grant
  - Hugh Bonneville
image: https://m.media-amazon.com/images/M/MV5BNTk1YzlhMTUtZmU5MC00NmRmLTlkZjItYzQ0NTY4Y2NiNzc4XkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 01-12-02018
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