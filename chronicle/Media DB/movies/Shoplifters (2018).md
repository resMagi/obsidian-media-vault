---
gf: true
type: movie
subType: ""
title: Shoplifters
englishTitle: Shoplifters
year: "2018"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt8075192/
id: tt8075192
plot: On the margins of Tokyo, a dysfunctional band of outsiders are united by loyalty, a penchant for petty theft and playful grifting. When the young son is arrested, secrets are exposed that upend their tenuous, below-the-radar exist...
genres:
  - Crime
  - Drama
  - Thriller
director:
  - Hirokazu Koreeda
writer:
  - Hirokazu Koreeda
studio:
  - N/A
duration: 121 min
onlineRating: 7.9
actors:
  - Lily Franky
  - Sakura Andô
  - Kirin Kiki
image: https://m.media-amazon.com/images/M/MV5BMjY2NGZlZDUtMDUwMi00YTUxLTljNzEtZTE3YjAyNTQyNzU5XkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 11-23-02018
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