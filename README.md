
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Assessing Coverage of Community-based Management of Acute Malnutrition

<!-- badges: start -->
<!-- badges: end -->

One of the most important elements behind the success of the
Community-Based Management of Acute Malnutrition (CMAM) model of service
delivery is its proven capacity for achieving and sustaining high levels
of coverage over wide areas.

Two-stage cluster sampled surveys have been used to estimate the
coverage of selective feeding programs. This approach suffers from
several important limitations. A new survey method for estimating the
coverage of selective feeding programs. This survey method, known as the
Centric Systematic Area Sampling (CSAS) method, uses a combination of
stratified and systematic area sampling and active and adaptive
case-finding. The CSAS survey method provides a rich set of information
about program coverage. In particular, provides a ‘headline’ estimate of
overall program coverage, a map of the spatial distribution of program
coverage, and a ranked list of program-specific barriers to service
access and uptake. The CSAS method is, however, resource intensive. This
has led to a tendency for it to be used for program evaluation rather
than for day-to-day program planning and program monitoring purposes The
results of CSAS surveys have, therefore, often been able to explain why
a particular program failed to achieve a satisfactory level and spatial
pattern of coverage, but this information has tended to arrive too late
in the program cycle to institute effective remedial action.

The CMAM model of service delivery is now being adopted in developmental
and post-emergency settings. Programs in these settings tend to suffer
from considerable resource scarcity compared to emergency-response
programs implemented by non-governmental organisations (NGOs). There
exists, therefore, a need for low-resource methods capable of evaluating
program coverage, identifying barriers to service access and uptake, and
identifying appropriate actions for improving access and program
coverage. This document describes two such methods – the
semi-quantitative evaluation of access and coverage (SQUEAC) method and
the simplified Lot Quality Assurance Sampling evaluation of access and
coverage (SLEAC) method – and how they can be used to investigate and
improve three aspects of CMAM programs: effectiveness, coverage, and
ability to meet need.

## About this repository

This repository contains the `Rmarkdown` script and related materials
used to produce the slide deck for the Assessing Coverage of
Community-based Management of Acute Malnutrition presentation for he
Nutrition in Emergencies (NiE) Module, MSc Nutrition for Global Health,
London School of Hygiene and Tropical Medicine on the 1st of March 2022.

## The slide deck

The slide deck was created using [Yihui Xie’s `{xaringan}`
package](https://github.com/yihui/xaringan) and Garrick Aden-Buie’s
ninja-themed presentation Rmarkdown template from his
[`{xaringanthemer}`
package](https://github.com/gadenbuie/xaringanthemer).

The **Rmarkdown** document is named `index.Rmd`. The **Rmarkdown**
document relies on additional resources to produce the slide deck. These
are:

-   `xaringan-themer.css` - this is the CSS that comes included when
    using the [`{xaringanthemer}`
    package](https://github.com/gadenbuie/xaringanthemer)’s ninja-themed
    presentation template. This CSS file is dynamically re-generated
    using new style specifications used in the **Rmarkdown** document

-   `libs` folder - this directory contains javascript libraries used by
    [`{xaringanthemer}`
    package](https://github.com/gadenbuie/xaringanthemer) to generate
    the HTML slides

-   `figures` folder - contains graphics used in the slides

These abovementioned four files are what is needed to reproduce the
slide deck using the following command in R:

``` r
rmarkdown::render(input = "index.Rmd", output_file = "index.html")
```

## Author

[Ernest Guevarra](https://ernest.guevarra.io)

## License

This work is licensed under a [GNU General Public License 3
(GPL-3)](https://github.com/ernestguevarra/coverageCMAM/blob/master/LICENSE.md).
