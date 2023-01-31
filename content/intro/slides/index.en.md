---
outputs:
- Reveal
title: Become an R Package Developer!
hidden: true
layout: list
weight: 11
output: hugodown::md_document
countdown: true
rmd_hash: 86c5e8e4cf7786a0

---

# Become an R Package Developer!

:wave: Hello!

------------------------------------------------------------------------

## Bonjour from Nancy !

<div class="highlight">

</div>

<div class="highlight">

{{< figure src="4843787.jpeg" alt="View from the Stanislas square in Nancy" caption="Picture by [Dimitry Anikin on Pexels](https://www.pexels.com/photo/aged-historical-porte-desilles-triumphal-arch-on-cloudy-day-4843787/)." width="600" >}}

</div>

------------------------------------------------------------------------

## My R package development creds

I really :heart: R package development

-   Volunteer editor for [rOpenSci Software Peer Review](https://ropensci.org/software-review).

-   At work, maintenance of [rOpenSci dev guide](https://devguide.ropensci.org).

-   Created the [R-hub blog](https://blog.r-hub.io).

-   Worked on the [HTTP testing in R](https://books.ropensci.org/http-testing/) book.

------------------------------------------------------------------------

## My R package development creds

Contributed to

-   [pkgdown 2.0.0](https://www.tidyverse.org/blog/2021/12/pkgdown-2-0-0/) (to produce documentation websites for packages)

-   [fledge 0.1.0](https://cynkra.github.io/fledge/) (Smoother change tracking and versioning for R packages)

-   [glitter 0.1.0](https://lvaudor.github.io/glitter/) (a SPARQL domain-specific language)

------------------------------------------------------------------------

## Why develop an R package?

Easiest way to share code/data/R Markdown templates... with

-   (future) you,

-   the collaborators you know,

-   and the collaborators you don't.

------------------------------------------------------------------------

## Why learning about package development?

[Jon Calder](https://joncalder.co.za/)'s very good [wording](https://github.com/iandurbach/datasci-fi/tree/master/docs/packages/slides)

-   To share code (and data);

-   To leverage existing tooling;

-   To contribute to other packages.

------------------------------------------------------------------------

## Who can write a package? YOU!

Susan Johnston's [wise words](https://github.com/susjoh/fibonacci).

-   Can you open R or RStudio?

-   Can you install a package?

-   Have you ever written a function in R?

-   Could you *learn* how to write a function in R?

:arrow_right: **You can write a package in R!**

------------------------------------------------------------------------

## Learn about functions

-   [Materials from Stephanie Kirmer's R-Ladies East Lansing tutorial](https://github.com/rladies-eastlansing/2021-rfunctions#writing-r-functions)

-   [Write your own R functions](https://stat545.com/functions-part1.html), stat 545 course by Jenny Bryan and The STAT 545 TAs;

-   [Chapter about functions](https://r4ds.had.co.nz/functions.html) in the book "R for Data Science" by Garrett Grolemund and Hadley Wickham;

-   [Fun with Functions talk](https://zealous-wiles-e22e83.netlify.app/talk/funwithfunctions/) by Kaylea Haynes, R-Ladies Manchester.

------------------------------------------------------------------------

## What is a package?

> Pour réduire ses craintes, il faut se dire que ce n'est ni plus ni moins qu'un dossier organisé d'une manière contrainte.

> To be less afraid you have to tell yourself that it's simply a folder organized in a constrained way.

[Sébastien Rochette](https://thinkr.fr/transformer-plusieurs-scripts-eparpilles-en-beau-package-r)

------------------------------------------------------------------------

## Automation!

{{< figure src="automate_meme.jpg" alt="Small monster saying to automate all the things" caption="Meme image by [Allie Brosh](https://en.wikipedia.org/wiki/Hyperbole_and_a_Half)" >}}

------------------------------------------------------------------------

## Automating... How?

Remember Clippy?

------------------------------------------------------------------------

## Automating... How?

Get to know an actually useful Clippy, `{usethis}`!

{{< figure src="https://usethis.r-lib.org/reference/figures/logo.png" alt="usethis logo, a robot" >}}

------------------------------------------------------------------------

## Why automate package development?

Easier to do, easier to teach.

You will create more packages than you think: for real usage, but also for reproducing problems.

------------------------------------------------------------------------

## Goals for today

-   Get to know (the best :innocent:) tools for package development;

-   Learn that there is no magic, only practice and :sparkles: tips :sparkles:.

------------------------------------------------------------------------

## Website tour

:link: <https://rpkgdev-mechanics.netlify.app/>

Slides, notes from the demo, further resources, comments!

------------------------------------------------------------------------

## Time for a demo :rocket:

Notes on the [course website](/intro/demo).

Also refer to the [Whole game chapter of the R packages book by Hadley Wickham and Jenny Bryan](https://r-pkgs.org/whole-game.html).

------------------------------------------------------------------------

## Back from the demo

-   [`devtools::load_all()`](https://devtools.r-lib.org/reference/load_all.html) (and then install)

-   `{usethis}` for all the things.

------------------------------------------------------------------------

## R CMD check (devtools::check())

<div class="highlight">

{{< figure src="1616781.jpeg" alt="East Berlin pedestrian traffic light" caption="Picture by [Jos van Ouwerkerk on Pexels](https://www.pexels.com/photo/selective-focus-photography-of-traffic-light-1616781/)." width="300" >}}

</div>

------------------------------------------------------------------------

## So what's really hard?

-   Writing good code.

-   Writing a good interface.

-   Writing good docs.

------------------------------------------------------------------------

## More with packages

-   [`usethis::use_rmarkdown_template()`](https://usethis.r-lib.org/reference/use_rmarkdown_template.html).

-   Distributing data [`usethis::use_data()`](https://usethis.r-lib.org/reference/use_data.html).

-   Packaging a Shiny app (look for examples, and [golemverse](https://golemverse.org/)).

-   Reproducible analyses, [research compendium](https://annakrystalli.me/rrresearch/10_compendium.html).

------------------------------------------------------------------------

## Less with packages

-   If developing a package for wider distribution, check it does not exist yet.

-   Miles McBain's post ["Project as an R package: An okay idea"](https://milesmcbain.xyz/posts/an-okay-idea/).

------------------------------------------------------------------------

## Questions?

See you at the next package development training?

