---
gf: false
type: movie
subType: ""
title: The Silence of the Lambs
englishTitle: The Silence of the Lambs
year: "1991"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0102926/
id: tt0102926
plot: A young F.B.I. cadet must receive the help of an incarcerated and manipulative cannibal killer to help catch another serial killer, a madman who skins his victims.
genres:
  - Crime
  - Drama
  - Horror
director:
  - Jonathan Demme
writer:
  - Thomas Harris
  - Ted Tally
studio:
  - N/A
duration: 118 min
onlineRating: 8.6
actors:
  - Jodie Foster
  - Anthony Hopkins
  - Scott Glenn
image: https://m.media-amazon.com/images/M/MV5BNDdhOGJhYzctYzYwZC00YmI2LWI0MjctYjg4ODdlMDExYjBlXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 02-14-01991
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