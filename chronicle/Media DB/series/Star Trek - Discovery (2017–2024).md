---
gf: false
type: series
subType: ""
title: "Star Trek: Discovery"
englishTitle: "Star Trek: Discovery"
year: 2017–2024
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt5171438/
id: tt5171438
plot: Ten years before Kirk, Spock, and the Enterprise, the USS Discovery discovers new worlds and lifeforms as one Starfleet officer learns to understand all things alien.
genres:
  - Action
  - Adventure
  - Drama
writer:
  - Bryan Fuller
  - Alex Kurtzman
studio: []
episodes: 0
duration: 60 min
onlineRating: 7
actors:
  - Sonequa Martin-Green
  - Anthony Rapp
  - Doug Jones
image: https://m.media-amazon.com/images/M/MV5BOTZkZTc1ZmYtYTA3Mi00MzZhLWFmZTItZTM2NThjYWJlZGU4XkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
airing: false
airedFrom: 09-24-02017
airedTo: unknown
watched: false
lastWatched: ""
personalRating: 6
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