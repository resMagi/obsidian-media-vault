---
gf: false
type: series
subType: ""
title: Gravity Falls
englishTitle: Gravity Falls
year: 2012–2016
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt1865718/
id: tt1865718
plot: Twin siblings Dipper and Mabel Pines spend the summer at their great-uncle's tourist trap in the enigmatic Gravity Falls, Oregon.
genres:
  - Animation
  - Adventure
  - Comedy
writer:
  - Alex Hirsch
studio: []
episodes: 0
duration: 23 min
onlineRating: 8.9
actors:
  - Jason Ritter
  - Alex Hirsch
  - Kristen Schaal
image: https://m.media-amazon.com/images/M/MV5BMTEzNDc3MDQ2NzNeQTJeQWpwZ15BbWU4MDYzMzUwMDIx._V1_SX300.jpg
released: true
streamingServices: []
airing: false
airedFrom: 06-15-02012
airedTo: unknown
watched: true
lastWatched: ""
personalRating: 9
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