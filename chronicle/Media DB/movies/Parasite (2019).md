---
gf: false
type: movie
subType: ""
title: Parasite
englishTitle: Parasite
year: "2019"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt6751668/
id: tt6751668
plot: Greed and class discrimination threaten the newly formed symbiotic relationship between the wealthy Park family and the destitute Kim clan.
genres:
  - Drama
  - Thriller
director:
  - Bong Joon Ho
writer:
  - Bong Joon Ho
  - Han Jin-won
studio:
  - N/A
duration: 132 min
onlineRating: 8.5
actors:
  - Song Kang-ho
  - Lee Sun-kyun
  - Cho Yeo-jeong
image: https://m.media-amazon.com/images/M/MV5BYjk1Y2U4MjQtY2ZiNS00OWQyLWI3MmYtZWUwNmRjYWRiNWNhXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 11-08-02019
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