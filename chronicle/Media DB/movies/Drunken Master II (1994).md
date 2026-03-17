---
gf: false
type: movie
subType: ""
title: Drunken Master II
englishTitle: Drunken Master II
year: "1994"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0111512/
id: tt0111512
plot: A young martial artist is caught between respecting his pacifist father's wishes or stopping a group of disrespectful foreigners from stealing precious artifacts.
genres:
  - Action
  - Comedy
director:
  - Chia-Liang Liu
  - Jackie Chan
writer:
  - Edward Tang
  - Man-Ming Tong
  - Kai-Chi Yuen
studio:
  - N/A
duration: 102 min
onlineRating: 7.5
actors:
  - Jackie Chan
  - Ho-Sung Pak
  - Lung Ti
image: https://m.media-amazon.com/images/M/MV5BNzBlMGZlZTctODdmYi00N2ZkLThkYjItZDdiNTQzNWIxMjAzXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 10-20-02000
watched: true
lastWatched: ""
personalRating: 8
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