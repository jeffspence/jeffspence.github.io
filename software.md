---
layout: page
title: software and data
permalink: /software/
---

# software:
[pyrho](#pyrho)  
[defiNETti](#definetti)  

<br>
# data:
[human recombination maps](#fine-scale-human-recombination-maps)  
[neanderthal introgression calls](#neanderthal-introgression-calls)

<br>
<br>
<br>
# [pyrho](https://github.com/popgenmethods/pyrho)
__fast inference of fine-scale recombination rates__ 
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
# [fine-scale human recombination maps](https://drive.google.com/drive/folders/1Tgt_7GsDO0-o02vcYSfwqHFd3JNF6R06)
__accurate, population-specific fine-scale recombination maps
for 26 populations__ 
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
we called tracts of neanderthal introgression in ceu, chb, and chs using our
method, [dical-admix](http://dical-admix.sourceforge.net).
the method and an analysis of the tracts are presented in our
[paper](https://doi.org/10.1111/mec.14565).
