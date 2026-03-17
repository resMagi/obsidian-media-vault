---
gf: false
type: series
subType: ""
title: Adventure Time
englishTitle: Adventure Time
year: 2010–2018
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt1305826/
id: tt1305826
plot: A 12-year-old boy and his best friend, a wise 28-year-old dog with magical powers, go on a series of surreal adventures in a remote future.
genres:
  - Animation
  - Action
  - Adventure
writer:
  - Pendleton Ward
studio: []
episodes: 0
duration: 11 min
onlineRating: 8.6
actors:
  - John DiMaggio
  - Jeremy Shada
  - Tom Kenny
image: https://m.media-amazon.com/images/M/MV5BMjkxMzIwNmQtMzM5Ni00YWJiLTg4YjQtNjBiN2IxMjZhMGQ2XkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
airing: false
airedFrom: 04-05-02010
airedTo: unknown
watched: false
lastWatched: ""
personalRating: 8
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