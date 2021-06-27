+++
# Date this page was created.
date = "2017-11-04"

# Project title.
title = "Marine invertebrates metabolism"

# Project summary to display on homepage.
summary = "Developing statistical tools to understand the metabolic rates of marine invertebrates."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "bugula_live.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["invertebrates", "metabolism", "respiration", "oxygen concentration", "Port Phillip Bay", "R", "Open Science", "Reproducibility", "Bayesian", "GitHub", "energetics"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/lagosFig2.png"
caption = "[Lagos et al. 2017](../../publication/lagos-2017-gcb), Fig. 2"

+++

Novel technologies (e.g. [PreSens SensorDish Reader](https://www.presens.de/products/detail/sdr-sensordishr-reader-basic-set.html)) have greatly advanced our capacity to measure respiratory rates of living organisms. These high throughput equipment also dump large amounts of data, and we still lack automated software capable of processing it. [Olito et al. 2017](../../publication/olito-2017-jeb) have proposed an empirical, reproducible method to estimate biological rates which are routinely estimated from non-linear and noisy time series data using linear regression and ad hoc manual truncation of non-linearities. The package allows the user to automate rate estimation across a list of files (dumped from hardware) with very few lines of code. This is now published as an [R package](https://github.com/colin-olito/LoLinR) named *LoLinR*, and it is freely available for download on [GitHub](https://github.com/).

Marine artificial structures are proliferating worldwide and provide a haven for marine invasive species. Such structures disrupt local hydrodynamics, which can lead to the formation of oxygen-depleted microsites. The extent to which native fauna can cope with such low oxygen conditions, and whether invasive species, long associated with artificial structures in flow-restricted habitats, have adapted to these conditions remains unclear. [Lagos et al. 2017](../../publication/lagos-2017-gcb) measured water flow and oxygen availability in marinas and piers at the scales relevant to sessile marine invertebrates (mm). We then proposed a novel statistical method based on Michaelis-Menten curves to estimate critical oxygen levels of marine organisms. The [code](https://github.com/dbarneche/vo2Inverts) is freely available on [GitHub](https://github.com/).
