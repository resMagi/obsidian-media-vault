---

gf: false
type: movie
subType: ""
title: The Raid 2
englishTitle: The Raid 2
year: "2014"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt2265171/
id: tt2265171
plot: Only a short time after the first raid, Rama goes undercover with the thugs of Jakarta and plans to bring down the syndicate and uncover the corruption within his police force.
genres:
  - Action
  - Crime
  - Thriller
director:
  - Gareth Evans
writer:
  - Gareth Evans
studio:
  - N/A
duration: 150 min
onlineRating: 7.9
actors:
  - Iko Uwais
  - Yayan Ruhian
  - Arifin Putra
image: https://m.media-amazon.com/images/M/MV5BMDMyNTMzZmYtNDIxYi00YTNkLWE2ZTMtM2M4ZGQwYTFjZTEyXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 04-11-02014
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