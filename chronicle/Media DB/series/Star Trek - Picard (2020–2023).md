---
gf: false
type: series
subType: ""
title: "Star Trek: Picard"
englishTitle: "Star Trek: Picard"
year: 2020–2023
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt8806524/
id: tt8806524
plot: "Follow-up to Star Trek: The Next Generation (1987) that centers on Jean-Luc Picard in the next chapter of his life."
genres:
  - Action
  - Adventure
  - Drama
writer:
  - Kirsten Beyer
  - Michael Chabon
  - Akiva Goldsman
studio: []
episodes: 0
duration: 46 min
onlineRating: 7.5
actors:
  - Patrick Stewart
  - Michelle Hurd
  - Jeri Ryan
image: https://m.media-amazon.com/images/M/MV5BODEzZWRiYWQtYjMwYi00YThhLWE4OWEtMzY2MWMxNWNhYzY5XkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
airing: false
airedFrom: 01-23-02020
airedTo: unknown
watched: false
lastWatched: ""
personalRating: 5
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