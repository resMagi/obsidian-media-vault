---
gf: true
type: movie
subType: ""
title: Fantastic Mr. Fox
englishTitle: Fantastic Mr. Fox
year: "2009"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt0432283/
id: tt0432283
plot: An urbane fox cannot resist returning to his farm raiding ways and then must help his community survive the farmers' retaliation.
genres:
  - Animation
  - Adventure
  - Comedy
director:
  - Wes Anderson
writer:
  - Roald Dahl
  - Wes Anderson
  - Noah Baumbach
studio:
  - N/A
duration: 87 min
onlineRating: 7.9
actors:
  - George Clooney
  - Meryl Streep
  - Bill Murray
image: https://m.media-amazon.com/images/M/MV5BYTA1ZTIxZDUtNGFjYS00YTc5LTgzNDMtZWNjYjBlMzI2OTk3XkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 11-25-02009
watched: false
lastWatched: ""
personalRating: 0
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