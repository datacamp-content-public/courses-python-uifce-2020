---
title: 'Chapter Title Here'
description: 'Chapter description goes here.'
---

## Example coding exercise

```yaml
type: NormalExercise
key: e8c1edbe67
lang: python
xp: 100
skills: 2
```

Para este ejercicio, deberán de realizar un programa que pueda mostrar un triangulo rectangulo creado con asteriscos. En asteriscos, la altura y el ancho de este triangulo debe de ser de 15 asteriscos. **NOTA:** Utilizar la pista disponible, implica perder la puntuación total de la actividad

`@instructions`


`@hint`


`@pre_exercise_code`
```{python}
import numpy as np
```

`@sample_code`
```{python}

```

`@solution`
```{python}
import numpy as np

for a in range(1,15):
    for b in range(1,15):
        if b <= a:
            print("*", end = "")
        if b == a:
            print("")

```

`@sct`
```{python}

```
