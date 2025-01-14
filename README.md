

<!-- README.md is generated from README.qmd. Please edit that file -->

# Designing ggtime: a grammar of temporal graphics

<!-- badges: start -->

<!-- badges: end -->

Slides and notes for an discussion presentation to the ggextenders group
(XX February 2025).

<!-- A recording of this presentation is available on YouTube here: <https://www.youtube.com/watch?v=> -->

<!-- [![](preview.jpg)](https://www.youtube.com/watch?v=) -->

#### Abstract

There are many visual idioms in place for plotting time series data,
however little work has been done to express them as elements of a
unified grammar of temporal graphics. The ggtime package extends ggplot2
with new grammatical elements for presenting temporal patterns. These
elements can be composed together to create familiar visual idioms, and
also recombined in new ways to create new informative plots. Temporal
visualisation requires special handling to accomodate calendrical quirks 
(similar to spatial, graph, and uncertainty visualisation). 
In this ggextenders talk I will introduce some design-stage development
of the ggtime package, and pose some technical discussion questions about 
engineering and designing ggplot2 extensions.

#### Structure

- Background (time as a special dimension, relate mixtime/ggtime to
  distributional/ggdist)

- Existing work producing visual idioms (feasts, sugrrants, gravitas)

- Design philosophy: use grammar layers to extend time independently of
  other layers (ggtime :heart: ggdist)

- Design decision discussions

  Start with the question prompt, along with some related work and
  necessary info.

  - Design decision 1: implementation of `coord_calender()`
  - Design decision 2: `geom_time_line()` or
    `position_civil()`/`position_absolute()` for civil/absolute time
  - Design decision 3: circular time as a position? data pre-processing

### Format

1 hour total (including discussion)
