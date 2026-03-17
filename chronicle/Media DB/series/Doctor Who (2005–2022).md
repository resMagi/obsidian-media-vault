---
gf: false
type: series
subType: ""
title: Doctor Who
englishTitle: Doctor Who
year: 2005–2022
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0436992/
id: tt0436992
plot: Continuing on from Doctor Who (1963), this revival follows the further adventures of the Doctor and their companions as they encounter various alien threats and save civilizations on different planets and time periods.
genres:
  - Adventure
  - Drama
  - Sci-Fi
writer:
  - Sydney Newman
studio: []
episodes: 0
duration: 45 min
onlineRating: 8.5
actors:
  - Jodie Whittaker
  - Peter Capaldi
  - Pearl Mackie
image: https://m.media-amazon.com/images/M/MV5BZGVmY2RkZjAtZDAwMC00MmZhLThhMGItZmVlNzE4MTgyMWRkXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
airing: false
airedFrom: 03-17-02006
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