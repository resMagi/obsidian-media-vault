---
gf: false
type: series
subType: ""
title: "Star Trek: The Next Generation"
englishTitle: "Star Trek: The Next Generation"
year: 1987–1994
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0092455/
id: tt0092455
plot: Set almost 100 years after Captain Kirk's five-year mission, a new generation of Starfleet officers sets off in the U.S.S. Enterprise-D on its own mission to go where no one has gone before.
genres:
  - Action
  - Adventure
  - Drama
writer:
  - Gene Roddenberry
studio: []
episodes: 0
duration: 44 min
onlineRating: 8.7
actors:
  - Patrick Stewart
  - Brent Spiner
  - Jonathan Frakes
image: https://m.media-amazon.com/images/M/MV5BMmNiNTQ2YzYtODBjYy00ZWMwLTlmNWMtYWE1NTQ2ZTYyZmMwXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
airing: false
airedFrom: 09-28-01987
airedTo: unknown
watched: true
lastWatched: ""
personalRating: 10
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