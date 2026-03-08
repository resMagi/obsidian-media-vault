---

gf: false
type: movie
subType: ""
title: "The Raid: Redemption"
englishTitle: "The Raid: Redemption"
year: "2011"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt1899353/
id: tt1899353
plot: A S.W.A.T. team becomes trapped in a tenement run by a ruthless mobster and his army of killers and thugs.
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
duration: 101 min
onlineRating: 7.6
actors:
  - Iko Uwais
  - Ananda George
  - Ray Sahetapy
image: https://m.media-amazon.com/images/M/MV5BOGUxM2Q0MzItZDRmYy00ZWY1LWFiNzctNmY3Njg2ODJjZWNmXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 04-13-02012
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