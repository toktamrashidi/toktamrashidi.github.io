---
layout: page
permalink: /research/
title: research
description: Coherent emission and periodic variability in star-forming regions.
nav: true
nav_order: 1
---

Methanol masers trace the earliest stages of high-mass star formation, and some of
them flare on strikingly regular cycles — periods of weeks to months that repeat for
years. The flares themselves are the puzzle: their shapes, their rise and decay
times, and the relationship between flares in different transitions are not always
easy to account for by changes in maser amplification alone.

My work asks what else might be happening, and in particular whether the molecules in
a radiating region are emitting independently or cooperatively.

## Superradiance in periodic methanol masers

In an ordinary maser, molecules radiate independently and the emission is amplified
along the line of sight. In Dicke superradiance, the molecules become correlated and
radiate in phase, which changes both the intensity and the timing of what we see. The
difference shows up in the shape of a flare, which makes lightcurves a way of testing
which process dominates.

I model these sources by solving the Maxwell–Bloch equations for a radiating region
and fitting the result to monitoring data. For **G22.356+0.066** this reproduced the
periodic 6.7 GHz flaring with a single coherent model, and for **G9.62+0.20E** a
unified framework accounted for multiperiodic behaviour that is difficult to
interpret otherwise.

<!-- Replace with a real figure: a lightcurve with the model fit overlaid.
<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/g962_fit.png" title="Model fit to G9.62+0.20E" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Observed 6.7 GHz lightcurve of G9.62+0.20E with the Maxwell–Bloch model overlaid.
</div>
-->

## Competing channels in multi-level systems

Real molecules are not two-level systems. With more levels available, population can
leak along parallel transitions, and that leakage competes with the build-up of
coherence that superradiance requires. Whether a region ends up superradiant depends
on which process wins.

I work on three-level Λ-systems to make that competition explicit — how fast
population leakage has to be before it suppresses a superradiant cascade, and what
observational signatures distinguish the two regimes.

## Toward a catalogue of superradiance candidates

Modelling sources one at a time establishes that the mechanism is viable; it does not
tell us how common it is. I am working toward the first systematic catalogue of
superradiance candidates in astrophysics, combining period-analysis pipelines applied
to maser monitoring data with the modelling above, in collaboration with monitoring
teams in Poland, Japan and South Africa.

## Tools

Most of this needs numerical machinery that did not already exist. I write and
maintain one- and three-dimensional superradiance solvers, a three-level
Maxwell–Bloch package for parallel transitions, and pipelines for identifying and
classifying periodicity in maser monitoring data.
