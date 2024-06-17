---
layout: page
title: software and data
permalink: /software/
---

# software:
[wfmoments](#wfmoments) <br>
[fastDTWF](#fastdtwf) <br>
[vilma](#vilma) <br>
[pyrho](#pyrho) <br>
[defiNETti](#definetti)

<br>
# data:
[human recombination maps](#fine-scale-human-recombination-maps) <br> 
[neanderthal introgression calls](#neanderthal-introgression-calls) <br>
[gene-level loss-of-function constraint](#gene-level loss-of-function constraint)
<br>
<br>
<br>
# [wfmoments](https://github.com/jeffspence/wfmoments)
__fast calculation of heterozygosity under spatial models__
<br>
<br>
[wfmoments](https://github.com/jeffspence/wfmoments) can compute
the equilibrium and dynamics of expected heterozygosity under arbitrary
deme models. wfmoments will be described in a forthcoming paper.

<br>
<br>
<br>
# [fastDTWF](https://github.com/jeffspence/fastDTWF)
__fast calculation of likelihoods under the Discrete-Time Wright-Fisher model__
<br>
<br>
[fastDTWF](https://github.com/jeffspence/fastDTWF)
implements machinery for computing various likelihoods under the
Discrete-Time Wright-Fisher model. This includes computing frequency spectra and
transition mass functions. The machiney can handle quite general models incorporating
mutation and selection.  fastDTWF is described in this [paper](https://doi.org/10.1093/genetics/iyad168).

<br>
<br>
<br>
# [vilma](https://github.com/jeffspence/vilma)
__polygenic scores using variational inference on gwas summary statistics from multiple cohorts__
<br>
<br>
[vilma](https://github.com/jeffspence/vilma) is a method for building
polygenic scores and inferring effect size distributions (genetic archtecture)
from gwas summary statistics and ld reference panels. vilma can be applied
to one or two cohorts. vilma is described in this
[paper](https://www.biorxiv.org/content/10.1101/2022.04.18.488696v1).

<br>
<br>
<br>
# [pyrho](https://github.com/popgenmethods/pyrho)
__fast inference of fine-scale recombination rates__ 
<br>
<br>
[pyrho](https://github.com/popgenmethods/pyrho) is a method for inferring
fine-scale recombination maps from sequencing data from unrelated individuals
while taking demographic history into account.
it is substantially faster than [LDhat](http://ldhat.sourceforge.net) while 
attaining comparable or better accuracy. in our
[paper](http://dx.doi.org/10.1126/sciadv.aaw9206)
we use pyrho to infer fine-scale recombination maps for the 26 populations in phase 3
of the
[thousand genomes project](http://www.internationalgenome.org/faq/which-populations-are-part-your-study/)
for the two most recent builds of the human genome (hg19 and hg38).
those maps are available
[here](https://drive.google.com/drive/folders/1Tgt_7GsDO0-o02vcYSfwqHFd3JNF6R06).

<br>
<br>
<br>
# [defiNETti](https://github.com/popgenmethods/defiNETti)
__exchangeable neural networks__ 
<br>
<br>
[defiNETti](https://github.com/popgenmethods/defiNETti) is a wrapper for
[TensorFlow](https://www.tensorflow.org) that automatically builds
exchangeable neural networks (i.e., networks that enforce
permutation-invariance) and trains them using
'simulation-on-the-fly' as described in our
[paper](http://papers.nips.cc/paper/8078-a-likelihood-free-inference-framework-for-population-genetic-data-using-exchangeable-neural-networks).  named after
[bruno](https://en.wikipedia.org/wiki/Bruno_de_Finetti).

<br>
<br>
<br>
# [fine-scale human recombination maps](https://zenodo.org/records/11437540)
__accurate, population-specific fine-scale recombination maps
for 26 populations__ 
<br>
<br>
we inferred fine-scale recombination maps for each of the 26 populations
in phase 3 of the
[thousand genomes project](http://www.internationalgenome.org/faq/which-populations-are-part-your-study/)
using our method
[pyrho](https://github.com/popgenmethods/pyrho).  the maps were
inferred while taking demography into account and explain patterns of
ld better than previous recombination maps.  the method and recombination
maps are described in our
[paper](http://dx.doi.org/10.1126/sciadv.aaw9206).
these recombination maps are also available for use in simulations
via the wonderful [stdpopsim](https://stdpopsim.readthedocs.io/en/latest/) project.


<br>
<br>
<br>
# [neanderthal introgression calls](https://drive.google.com/drive/folders/0B_RxlKHkUXRDflZDd0xWTEVNWVF2OFppUmNka3ZWN19pbU5qVjBVV2lGVVBuQTJkWE5KTDg)
__posterior probabilities of introgression in modern humans__ 
<br>
<br>
we called tracts of neanderthal introgression in ceu, chb, and chs using our
method, [dical-admix](http://dical-admix.sourceforge.net).
the method and an analysis of the tracts are presented in our
[paper](https://doi.org/10.1111/mec.14565).


<br>
<br>
<br>
# [gene-level loss-of-function constraint](https://zenodo.org/records/10403680)
__estimates of the strength of selection against loss-of-function variants__
<br>
<br>
we developed powerful machinery to combine information across genes,
[GeneBayes](https://github.com/tkzeng/GeneBayes), to estimate the strength of selection acting against
loss-of-function variants in almost every gene in the human genome. the method
and an analysis of the constraint measures are presented in our
[paper](https://www.biorxiv.org/content/10.1101/2023.05.19.541520).
