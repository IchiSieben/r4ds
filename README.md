# r4ds

Personal fork of the source repository for [*R for Data Science*](http://r4ds.had.co.nz) by Hadley Wickham and Garrett Grolemund, kept for reference. As of this writing the fork contains **no commits or original content by the fork owner** — it is an unmodified copy of the upstream book source (chapters as `.Rmd` files, `bookdown` config, diagrams, data).

## How to run

This is a [bookdown](https://github.com/rstudio/bookdown) project (upstream's own instructions):

```r
devtools::install_github("hadley/r4ds")
bookdown::render_book(".")
```

Requires [pandoc](http://johnmacfarlane.net/pandoc/) and the packages listed in `DESCRIPTION`. **Not verified in this fork**: the `Remotes:` field pins package versions from 2017 (`hadley/ggplot2`, `slowkow/ggrepel`, `rstudio/bookdown`, `rstudio/rmarkdown`), so a build against a current R/tidyverse install is unlikely to succeed without adjustment.

## Licence

Content is upstream's, under the existing [`LICENSE`](./LICENSE) file: Creative Commons Attribution-NonCommercial-NoDerivs 3.0 United States (CC BY-NC-ND 3.0 US). No separate licence is added here, since there is no original work of the fork owner to license.

## Fork maintained by

Yoichi Palacios Tanaka (IchiSieben) · ichisieben.dev

---

## Español

Fork personal del repositorio fuente de [*R for Data Science*](http://r4ds.had.co.nz), de Hadley Wickham y Garrett Grolemund, conservado como referencia. A la fecha, el fork **no tiene commits ni contenido original del dueño del fork**: es una copia sin modificar del código fuente del libro (capítulos en `.Rmd`, configuración de `bookdown`, diagramas, datos).

## Cómo correrlo

Es un proyecto [bookdown](https://github.com/rstudio/bookdown) (instrucciones propias del repositorio original):

```r
devtools::install_github("hadley/r4ds")
bookdown::render_book(".")
```

Requiere [pandoc](http://johnmacfarlane.net/pandoc/) y los paquetes listados en `DESCRIPTION`. **No verificado en este fork**: el campo `Remotes:` fija versiones de paquetes de 2017 (`hadley/ggplot2`, `slowkow/ggrepel`, `rstudio/bookdown`, `rstudio/rmarkdown`), por lo que una compilación contra un R/tidyverse actual probablemente no funcione sin ajustes.

## Licencia

El contenido es del autor original, bajo el archivo [`LICENSE`](./LICENSE) ya existente: Creative Commons Attribution-NonCommercial-NoDerivs 3.0 United States (CC BY-NC-ND 3.0 US). No se agrega una licencia aparte porque no hay obra original del dueño del fork que licenciar.

## Fork mantenido por

Yoichi Palacios Tanaka (IchiSieben) · ichisieben.dev
