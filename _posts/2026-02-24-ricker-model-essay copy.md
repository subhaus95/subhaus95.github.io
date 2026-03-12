---
layout: post
title: "Yes, but why?"
date: 2026-03-09
author: paul-hobson
excerpt: "How did a short weekend project to rebuild a bunch of Jekyll templates balloon into a publishing pipeline?"
categories: [writing]
tags: [modelling, environment, jekyll, blogging, interests]
# Viz flags — body classes for core.js CDN detection
math: true
viz: true
comments: true
---



## Introduction

The Ricker model<cite data-cite="Ricker, W.E. (1954). Stock and Recruitment. Journal of the Fisheries Research Board of Canada 11(5):559–623."></cite> describes how a population changes from one generation to the next:

$$
N_{t+1} = N_t \cdot r \cdot e^{-N_t / K}
$$

where $N_t$ is the population at time $t$, $r$ is the intrinsic growth rate, and $K$ is the carrying capacity.

## Interactive model

The widget below lets you explore how $r$ changes the long-run dynamics. Try dragging the slider.

<div data-viz="ricker" style="height: 360px;"></div>

## Stability analysis

For small values of $r$, the population converges to a fixed point. As $r$ increases, period-doubling bifurcations appear — and eventually the dynamics become chaotic.

<span class="sidenote-anchor" data-sn="1">The period-doubling route to chaos</span> was described by Robert May in his landmark 1976 *Nature* paper, which showed that even simple ecological models produce unpredictable dynamics.

<aside class="sidenote" data-sn="1">
May, R.M. (1976). Simple mathematical models with very complicated dynamics. <em>Nature</em> 261, 459–467.
</aside>

## Callout example

<div class="callout callout-note">
  <span class="callout-icon">💡</span>
  <div class="callout-body">
    <p>At $r = 2.692$, the Ricker model enters its first period-doubling bifurcation. The population alternates between two values rather than settling at a fixed point.</p>
  </div>
</div>

## References
