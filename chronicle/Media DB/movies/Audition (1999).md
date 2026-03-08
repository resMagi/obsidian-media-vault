---

gf: false
type: movie
subType: ""
title: Audition
englishTitle: Audition
year: "1999"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0235198/
id: tt0235198
plot: A widower has his film producer friend organize a fake audition as a means of helping him find a new girlfriend, but the woman he selects is not who she appears to be.
genres:
  - Drama
  - Horror
  - Mystery
director:
  - Takashi Miike
writer:
  - Ryû Murakami
  - Daisuke Tengan
studio:
  - N/A
duration: 115 min
onlineRating: 7.1
actors:
  - Ryô Ishibashi
  - Eihi Shiina
  - Tetsu Sawaki
image: https://m.media-amazon.com/images/M/MV5BMTI5MmFlZjgtNjNhNC00NTFlLWEzZTctYjNjZDdjYjVmNjExXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 03-03-02000
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