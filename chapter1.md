---
title       : Insert the chapter title here
description : Insert the chapter description here
attachments :
  slides_link : https://s3.amazonaws.com/assets.datacamp.com/course/teach/slides_example.pdf


--- type:NormalExercise lang:r xp:100 skills:1 key:6a715c8c19
## describe


*** =instructions

*** =hint

*** =pre_exercise_code
```{r}

```

*** =sample_code
```{r}
library(psych)

describe(sat.act)

headTail(sat.act)
```

*** =solution
```{r}
library(psych)

describe(sat.act)

headTail(sat.act)
```

*** =sct
```{r}

```

--- type:NormalExercise lang:r xp:100 skills:1 key:b34509f3b3
## pairs.panels and outliers


*** =instructions

*** =hint

*** =pre_exercise_code
```{r}

```

*** =sample_code
```{r}
pairs.panels(sat.act)

outliers(sat.act)
```

*** =solution
```{r}
pairs.panels(sat.act)

outliers(sat.act)

```

*** =sct
```{r}

```

--- type:NormalExercise lang:r xp:100 skills:1 key:1626544591
## scrub


*** =instructions

*** =hint

*** =pre_exercise_code
```{r}

```

*** =sample_code
```{r}
scrub(sat.act, max = 9)
```

*** =solution
```{r}
scrub(sat.act, max = 9)
```

*** =sct
```{r}

```

--- type:NormalExercise lang:r xp:100 skills:1 key:d03d20c61e
## error.bars


*** =instructions

*** =hint

*** =pre_exercise_code
```{r}

```

*** =sample_code
```{r}
error.bars(sat.act)
```

*** =solution
```{r}
error.bars(sat.act)
```

*** =sct
```{r}

```

--- type:NormalExercise lang:r xp:100 skills:1 key:eea50db93a
## correlations


*** =instructions

*** =hint

*** =pre_exercise_code
```{r}

```

*** =sample_code
```{r}
library(psych)

lowerCor(sat.act)
corPlot(sat.act)
corr.test(sat.act)
```

*** =solution
```{r}
library(psych)

lowerCor(sat.act)
corPlot(sat.act)
corr.test(sat.act)

```

*** =sct
```{r}

```
