---
gf: false
type: movie
subType: ""
title: The King's Speech
englishTitle: The King's Speech
year: "2010"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt1504320/
id: tt1504320
plot: The story of King George VI, his unexpected ascension to the throne of the British Empire in 1936, and the speech therapist who helped the unsure monarch overcome his stammer.
genres:
  - Biography
  - Drama
  - History
director:
  - Tom Hooper
writer:
  - David Seidler
studio:
  - N/A
duration: 118 min
onlineRating: 8
actors:
  - Colin Firth
  - Geoffrey Rush
  - Helena Bonham Carter
image: https://m.media-amazon.com/images/M/MV5BMzU5MjEwMTg2Nl5BMl5BanBnXkFtZTcwNzM3MTYxNA@@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 12-25-02010
watched: true
lastWatched: ""
personalRating: 8.5
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