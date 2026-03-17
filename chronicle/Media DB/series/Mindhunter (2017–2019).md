---
gf: false
type: series
subType: ""
title: Mindhunter
englishTitle: Mindhunter
year: 2017–2019
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt5290382/
id: tt5290382
plot: In the late 1970s, two FBI agents broaden the realm of criminal science by investigating the psychology behind murder and end up getting too close to real-life monsters.
genres:
  - Crime
  - Drama
  - Mystery
writer:
  - Joe Penhall
studio: []
episodes: 0
duration: 60 min
onlineRating: 8.6
actors:
  - Jonathan Groff
  - Holt McCallany
  - Anna Torv
image: https://m.media-amazon.com/images/M/MV5BYTk4NDA4MGMtNjliOC00MjExLWI1YzctOTc4NWIxM2I1YjM5XkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
airing: false
airedFrom: 10-13-02017
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