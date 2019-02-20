---
layout: page
title: software
permalink: /software/
---

# [pyrho](https://github.com/popgenmethods/pyrho)
__fast inference of fine-scale recombination rates__  
[pyrho](https://github.com/popgenmethods/pyrho) is a method for inferring
fine-scale recombination maps from sequencing data from unrelated individuals
while taking demographic history into account.
it is substantially faster than [LDhat](http://ldhat.sourceforge.net) while 
attaining comparable or better accuracy. in our
[preprint](https://doi.org/10.1101/532168)
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
[defiNETti](https://github.com/popgenmethods/defiNETti) is a wrapper for
[TensorFlow](https://www.tensorflow.org) that automatically builds
exchangeable neural networks (i.e., networks that enforce
permutation-invariance) and trains them using
'simulation-on-the-fly' as described in our
[paper](http://papers.nips.cc/paper/8078-a-likelihood-free-inference-framework-for-population-genetic-data-using-exchangeable-neural-networks).  named after
[bruno](https://en.wikipedia.org/wiki/Bruno_de_Finetti).
