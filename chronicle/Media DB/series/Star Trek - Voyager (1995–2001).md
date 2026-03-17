---
gf: false
type: series
subType: ""
title: "Star Trek: Voyager"
englishTitle: "Star Trek: Voyager"
year: 1995–2001
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0112178/
id: tt0112178
plot: Pulled to the far side of the galaxy, where the Federation is seventy-five years away at maximum warp speed, the crew of the Starfleet star-ship Voyager must forge a truce with a group of Maquis rebels in order to find a way home.
genres:
  - Action
  - Adventure
  - Drama
writer:
  - Rick Berman
  - Michael Piller
  - Jeri Taylor
studio: []
episodes: 0
duration: 44 min
onlineRating: 7.9
actors:
  - Kate Mulgrew
  - Robert Beltran
  - Roxann Dawson
image: https://m.media-amazon.com/images/M/MV5BMmM2YjBjYzItYmFlOC00MDllLWJiOTQtNjY0MGY5NWI1MDFmXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
airing: false
airedFrom: 01-16-01995
airedTo: unknown
watched: true
lastWatched: ""
personalRating: 9.5
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