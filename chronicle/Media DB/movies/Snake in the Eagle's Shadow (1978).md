---
gf: false
type: movie
subType: ""
title: Snake in the Eagle's Shadow
englishTitle: Snake in the Eagle's Shadow
year: "1978"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0078252/
id: tt0078252
plot: An orphan who has been raised at a kung fu school, where he is treated as little more than a dogsbody and practice target for the students, has a life-changing experience after helping an old peripatetic beggar.
genres:
  - Action
  - Comedy
director:
  - Yuen Woo-Ping
writer:
  - Chi Yuan Hsi
  - Huo An Hsi
  - Lung Hsiao
studio:
  - N/A
duration: 90 min
onlineRating: 7.3
actors:
  - Jackie Chan
  - Siu-Tin Yuen
  - Jeong-lee Hwang
image: https://m.media-amazon.com/images/M/MV5BM2RhNTg3NjUtOTE0Zi00NGQ3LTgzM2UtMWEyMjAyNzg2Yzk4XkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 11-01-01982
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