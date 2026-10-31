---
layout: default
title: Stream Power Parameters
description: Developing and evaluating methods to estimate concavity and channel steepness in the stream power model.
---

<span class="eyebrow">RESEARCH THEME 02 · RIVER NETWORK ANALYSIS</span>

# Stream Power Parameters

The stream power incision model provides a widely used framework for understanding how rivers incise into bedrock and how river profiles respond to changes in tectonics and climate. Two important parameters in this model are the concavity index, commonly expressed as the ratio *m/n*, and the channel steepness index, *k*ₛ. Their accurate estimation is essential if river profiles are to be used to infer spatial and temporal variations in rock uplift.

## When does the concavity index constrain stream power parameters?

The concavity index is often estimated using methods that assume rock uplift rate and erodibility are spatially uniform. However, these conditions are rarely met in natural landscapes. Spatial variations — and particularly spatial gradients — in these processes can introduce systematic errors into commonly used estimates of *m/n*.

In this study, I develop a new method to estimate *m/n* using a large river-network topographic inversion. Rather than relying on the assumption of spatially uniform channel steepness, the inversion allows channel steepness to vary across the landscape while identifying the *m/n* value that best reproduces the observed topography. Tests using synthetic landscapes and real river networks from the Siwalik Hills and Olympic Mountains demonstrate that the method can recover reliable estimates where existing approaches may produce biased results. This provides a way to estimate a key stream power parameter in landscapes where uplift and erodibility vary spatially.

[Read the paper: When Does the Concavity Index Constrain Stream Power Parameters?](https://doi.org/10.1029/2023JF007584) · [Explore the INCA code](https://github.com/adamsmith142/INCA)

## Comparing methods for calculating channel steepness index

The channel steepness index, *k*ₛ, is widely used as a proxy for relative rock-uplift rate, but its value depends on how it is calculated. In this review, we compare the main approaches for estimating channel steepness using a synthetic river profile and a case study from the Sierra Nevada, California. We show that different methods can produce values that vary by orders of magnitude, potentially influencing the interpretation of tectonic signals. We discuss the strengths and limitations of each approach and emphasise that method selection should be guided by the question being addressed — and that the method used should always be clearly reported to make results reproducible and comparable.

[Read the paper: Comparing methods for calculating channel steepness index](https://doi.org/10.1016/j.earscirev.2022.103970)

[Back to research overview]({{ '/Research.html' | relative_url }})
