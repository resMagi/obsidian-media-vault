---
gf: false
type: movie
subType: ""
title: The Lighthouse
englishTitle: The Lighthouse
year: "2019"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt7984734/
id: tt7984734
plot: Two lighthouse keepers try to maintain their sanity while living on a remote and mysterious New England island in the 1890s.
genres:
  - Drama
  - Fantasy
  - Horror
director:
  - Robert Eggers
writer:
  - Robert Eggers
  - Max Eggers
studio:
  - N/A
duration: 109 min
onlineRating: 7.4
actors:
  - Robert Pattinson
  - Willem Dafoe
  - Valeriia Karaman
image: https://m.media-amazon.com/images/M/MV5BMTI4MjFhMjAtNmQxYi00N2IxLWJjMGEtYWY1YmU3OTQ0Zjk3XkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 11-01-02019
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