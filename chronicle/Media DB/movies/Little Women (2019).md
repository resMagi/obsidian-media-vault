---
gf: true
type: movie
subType: ""
title: Little Women
englishTitle: Little Women
year: "2019"
dataSource: OMDbAPI
url: https://www.imdb.com/title/tt3281548/
id: tt3281548
plot: In 19th century Massachusetts, the March sisters--Meg, Jo, Beth, and Amy--on the threshold of womanhood, go through many ups and downs in life and endeavor to make important decisions about their futures.
genres:
  - Drama
  - Romance
director:
  - Greta Gerwig
writer:
  - Greta Gerwig
  - Louisa May Alcott
studio:
  - N/A
duration: 135 min
onlineRating: 7.8
actors:
  - Saoirse Ronan
  - Emma Watson
  - Florence Pugh
image: https://m.media-amazon.com/images/M/MV5BMWMzYjNiZWMtMDg4NS00MDgyLTk5MWItOTFmNjg4NzRhZmExXkEyXkFqcGc@._V1_SX300.jpg
released: true
streamingServices: []
premiere: 12-25-02019
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