---
layout: page
title: Research
permalink: /research/
---


We work at the intersection of population genetics,
statistical genetics, and machine learning.
We use a combination of conceptual models,
pen-and-paper analysis of mathematical models,
and large-scale data analysis to understand
human genetics: from how mutations
impact cells all the way up to how those mutations are affected
by natural selection over hundreds of thousands of
years. Some of the things we are particular interested
in are:


### Methods for inferring and interpreting evolutionary constraint

The mutations that we see in a sample of present-day individuals
are an extremely biased subset of all possible mutations: they must
have survived the sieve of natural selection. That means that
we can use patterns of variation to figure out what parts of
the genome are constrained by natural selection and infer that
those parts must be functionally important.

Unfortunately, evolution is an extremely noisy process.
The frequency of a genetic variant is driven both by
natural selection and random genetic drift.  This makes
it very difficult to tell if any single variant is being
affected by selection.

To get around this, we are interested in developing machine learning
models to pool information across variants by leveraging
variant-level features (e.g., chromatin accessibility data or
deep mutational scanning data). We are also interested in
the other side of this coin: what variant-level features cause
a variant to be selected against.

Relevant papers:

*  Zeng, T.\* <sup>,</sup> &#8224;, __Spence, J. P.__\* <sup>,</sup> &#8224;, Mostafavi, H., and Pritchard, J. K.&#8224; [Bayesian estimation of gene constraint from an evolutionary model with gene features.](https://doi.org/10.1038/s41588-024-01820-9) _Nature Genetics_ (2024).

* __Spence, J. P.__&#8224;, Zeng, T., Mostafavi, H., and Pritchard, J. K. [Scaling the Discrete-time Wright-Fisher model to biobank-scale datasets.]( https://doi.org/10.1093/genetics/iyad168) _Genetics_ (2023).


### Causes and consequences of trait specificity

Genetic variants are often pleiotropic, meaning that they
impact multiple traits. One explanation of this is the
[omnigenic model](https://www.sciencedirect.com/science/article/pii/S0092867417306293):
the gene regulatory network within cells is sufficiently
well-connected such that perturbing the expression of
one gene affects the expression of many others, including
genes that have direct impacts on different traits.
Another explanation is that the machinery for different key cellular
processes is shared across many cell types, and disrupting
this machinery affects all of these cell types and the traits
they influence.

In recent work we showed that _trait-specific_ variants
contribute more to heritability and are prioritized higher
by association studies. Our work also hinted at a
broad spectrum of specificity across genes and variants,
including highly trait-specific variants acting on highly
pleiotropic genes. We are interested in understanding the 
cellular mechanisms by which
such trait specificity can arise.

Relevant paper:

* __Spence, J. P.__\*&#8224;, Mostafavi, H.\*&#8224;, Ota, M.&#8224;, Milind, N., Gjorgjieva, T., Smith, C. J., Simons, Y. B., Sella, G., and Pritchard, J. K.&#8224; [Specificity, length and luck drive gene rankings in association studies.](https://doi.org/10.1038/s41586-025-09703-7) _Nature_ (2025).


### Genetic impact of stabilizing selection on traits

Many traits, including risks for many diseases,
appear to be under _stabilizing selection_: 
it is disadvantageous to have a trait value 
that is too high _or_ too low. This is somewhat
surprising: having too low of a disease risk
can also be bad!

This results in fascinating dynamics at more granular
biological scales.  If a variant increases a trait
that is subject to stabilizing selection,
whether the variant is beneficial
or deleterious depends on whether it's acting in an
individual that has too little or too much of the trait.
This in turn depends on the effects of the other variants
that that individual has and how the environment impacts
the individual.
Similar considerations play out across biological scales:
increasing the expression of a gene expression program
may be helpful or hurtful depending on how it impacts
fitness-relevant traits, and whether in any given
individual, that moves them closer to or further from
having optimal trait values.

We are interested in better understanding how these effects
play out across different biological scales, by using
a combination of mathematical modeling and simulation.
We want to use these insights to understand 
the real-world consequences of stabilizing
selection: how does it impact what is discovered in
association studies? How does it shape proteins and gene regulatory networks?
Can we use these insights to improve genomic or protein language models?

Relevant papers:

* __Spence, J. P.__\*&#8224;, Mostafavi, H.\*&#8224;, Ota, M.&#8224;, Milind, N., Gjorgjieva, T., Smith, C. J., Simons, Y. B., Sella, G., and Pritchard, J. K.&#8224; [Specificity, length and luck drive gene rankings in association studies.](https://doi.org/10.1038/s41586-025-09703-7) _Nature_ (2025).

* Patel, R. A.&#8224;, Weiß, C. L., Zhu, H., Mostafavi, H., Simons, Y. B., __Spence, J. P.__&#8224;, and Pritchard, J. K.&#8224; [Characterizing selection on complex traits through conditional frequency spectra.](https://doi.org/10.1093/genetics/iyae210) _Genetics_ (2024).


### Population genetics of climate change

Anthropogenic climate change is driving the sixth mass extinction.
Beyond the loss of entire species, we are also witnessing threats
to genetic diversity within species.  This loss of genetic diversity
will make it harder for surviving species to adapt to a rapidly
changing environment.

With [Moisés Expósito-Alonso](https://www.moisesexpositoalonso.org/home)
we are using and building population genetics tools
to understand how climate change has impacted and will impact
genetic diversity. We are particularly interested in understanding
how genetic diversity is affected by the interaction of
geographical spatial structure in populations and
the spatial structure of habitat loss.

Relevant papers:

* Mualim, K. S.\*, __Spence, J. P.__\*, Weiß, C. L.\*, Selmoni, O., Lin, M., and Expósito-Alonso, M. [Genetic diversity loss in the Anthropocene will continue long after habitat destruction ends.](https://doi.org/10.1101/2024.10.21.619096) _bioRxiv preprint_.

*   Expósito-Alonso, M., Booker, T. R.<sup>&amp;</sup>, Czech, L.<sup>&amp;</sup>, Gillespie, L.<sup>&amp;</sup>, Hately, S.<sup>&amp;</sup>, Kyriazis, C. C.<sup>&amp;</sup>, Lang, P. L. M.<sup>&amp;</sup>, Leventhal, L.<sup>&amp;</sup>, Nogues-Bravo, D.<sup>&amp;</sup>, Pagowski, V.<sup>&amp;</sup>, Ruffley, M.<sup>&amp;</sup>, __Spence, J. P.__<sup>&amp;</sup>, Toro Arana, S. E.<sup>&amp;</sup>, Weiß, C. L.<sup>&amp;</sup>, and Zess, E.<sup>&amp;</sup>  [Genetic diversity loss in the Anthropocene.](https://doi.org/10.1126/science.abn5642) _Science_ (2022).
