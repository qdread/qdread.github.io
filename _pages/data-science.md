---
layout: archive
title: "Data Science"
permalink: /data-science/
author_profile: true
header:
  overlay_image: elkton-banner.jpg
  overlay_filter: 0.15
  caption: "Photo: QDR"
---

<a name="top"></a>

Quentin is committed to making data science open and reproducible and breaking down barriers that keep social and environmental researchers from using big publicly-available data. In practice, that means designing and teaching data science lessons, and creating and contributing to software packages for high-performance computing, data visualization, and ecological data analysis.

## Teaching Data Science

Since 2019, Quentin has created online data science lessons and taught them in-person and virtually as part of the data science team at [SESYNC](https://www.sesync.org). Quentin has either created or contributed to a whole host of lessons available on the [SESYNC cyberhelp page](https://cyberhelp.sesync.org/lesson). Topics include [basic][basicgit] and [advanced git][advancedgit], using R and APIs to [get online data][onlinedata], and [geospatial data][geospatial].

[Back to top](#top)

## R Packages

These are the R packages that Quentin has created or contributed to.

![rslurm hex logo](/images/logo_slurm.png){: .align-right .width-tiny }

### rslurm

Researchers working with big socio-environmental data are often familiar with synthesizing and analyzing data in R, but they run up on memory and processing time limitations. Many of their institutions provide high-performance computing clusters for running big computing jobs. But using those clusters requires knowledge of shell scripting, which many socio-environmental researchers don't have. The [rslurm][rslurm] package, originally created by Philippe Marchand, a SESYNC data scientist, solves this problem. It allows users to run computing jobs on a Slurm cluster directly from R! The package creates all the necessary shell scripts for you behind the scenes, and manages the jobs automatically. Quentin has been maintaining and contributing new features to the package since 2019.

![ggalluvial app screenshot](/images/ggalluvialscreenshot.png){: .align-left .width-half }

### ggalluvial

Quentin's contribution to the [ggalluvial][ggalluvial] package started when a research team asked him to work on an interactive visualization of their data. While he was making the Shiny app, he talked to the developer of [ggalluvial][ggalluvial] and wrote some code to make alluvial plots that the user can interact with. He wrote a [vignette][vignette] for the package so that other people could benefit from what he learned --- open data science at its finest! See a [demo app][demo] here.

![example Ostats multivariate plot](/images/ostatsmultiplot.PNG){: .align-right .width-less }

### Ostats

The [Ostats][Ostats] package was born out of a collaboration between Quentin and fellow postdoc John Grady back at Michigan State (see the [Research](/research/) page). It allows users to calculate "O-statistics,"  community-level pairwise niche overlap statistics, and to make plots to visualize community trait overlap patterns. Quentin is the lead developer of [Ostats][Ostats] and co-mentored two undergraduates who helped write the code.

[Back to top](#top)

[rslurm]: https://cyberhelp.sesync.org/rslurm/
[demo]: https://qdread.shinyapps.io/ex-shiny-wide-data/
[vignette]: http://corybrunson.github.io/ggalluvial/articles/shiny.html
[ggalluvial]: http://corybrunson.github.io/ggalluvial/
[Ostats]: https://neon-biodiversity.github.io/Ostats/
[basicgit]: https://cyberhelp.sesync.org/basic-git-lesson/
[advancedgit]: https://cyberhelp.sesync.org/advanced-git-lesson/
[onlinedata]: https://cyberhelp.sesync.org/online-data-with-R-lesson/
[geospatial]: https://cyberhelp.sesync.org/geospatial-packages-in-R-lesson/
