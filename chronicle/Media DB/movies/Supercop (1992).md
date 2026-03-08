---

gf: false
type: movie
subType: ""
title: Supercop
englishTitle: Supercop
year: "1992"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0104558/
id: tt0104558
plot: A Hong Kong detective teams up with his female Red Chinese counterpart to stop a Chinese drug czar.
genres:
  - Action
  - Comedy
  - Crime
director:
  - Stanley Tong
writer:
  - Edward Tang
  - Fibe Ma
  - Lee Wai Yee
studio:
  - N/A
duration: 91 min
onlineRating: 7
actors:
  - Jackie Chan
  - Michelle Yeoh
  - Maggie Cheung
image: https://m.media-amazon.com/images/M/MV5BMjVjYTFjMjItOGZiZS00ZjRlLThiMzUtOWVkMmE3YzE4ZGRkXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 07-26-01996
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