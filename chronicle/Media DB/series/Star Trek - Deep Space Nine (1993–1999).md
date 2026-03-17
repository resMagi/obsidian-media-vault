---

gf: false
type: series
subType: ""
title: "Star Trek: Deep Space Nine"
englishTitle: "Star Trek: Deep Space Nine"
year: 1993–1999
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0106145/
id: tt0106145
plot: In the vicinity of the liberated planet of Bajor, the Federation space station Deep Space Nine guards the opening of a stable wormhole to the far side of the galaxy.
genres:
  - Action
  - Adventure
  - Drama
writer:
  - Rick Berman
  - Michael Piller
studio: []
episodes: 0
duration: 45 min
onlineRating: 8.1
actors:
  - Avery Brooks
  - Rene Auberjonois
  - Cirroc Lofton
image: https://m.media-amazon.com/images/M/MV5BMzg3Mzg5ZmYtYTZhNy00NTQ4LWFiYjAtODYxODBlNDViMzYxXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
airing: false
airedFrom: 01-03-01993
airedTo: unknown
watched: false
lastWatched: ""
personalRating: 0
tags: mediaDB/tv/series
---

`$= '![Image|360](' + dv.current().image + ')'`

  

# `$= dv.current().title`


**Genres**:

```dataviewjs

dv.current().genres.length === 0 ? dv.span(' - none') : dv.list(dv.current().genres)

```

  

```dataviewjs

let text = '';

  

if (!dv.current().released) {

text += '**Not released**\n';

if (dv.current().airedFrom) {

text += 'The series will release on ' + dv.current().release_date + '.';

} else {

text += 'The series is not released yet.';

}

} else if (dv.current().airing) {

text += '**Not finished**\n';

text += 'The series is not fully released yet.';

}

  

if (text) {

dv.paragraph(text);

}

```

  

**Type**: `$= dv.current().type`

**Online Rating**: `$= dv.current().onlineRating`

**Episodes**: `$= dv.current().episodes`

**Duration**: `$= dv.current().duration`

**Aired from**: `$= dv.current().airedFrom`

**Aired until**: `$= dv.current().airedTo`

**Studios**: `$= dv.current().studios.join(', ')`

---
## Review

## Notes