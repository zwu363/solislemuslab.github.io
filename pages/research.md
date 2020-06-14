---
layout: page
title: Research
description: Solis-Lemus publications
---

<div class="navbar">
    <div class="navbar-inner">
        <ul class="nav">
            <li><a href="#phylogenomics">phylogenomics</a></li>
            <li><a href="#genomics">genomics</a></li>
            <li><a href="#dl">deeplearning</a></li>
            <li><a href="#microbiome">microbiome</a></li>
            <li><a href="#publications">publications</a></li>
            <li><a href="https://scholar.google.com/citations?user=GrUypj8AAAAJ&hl=en&oi=ao">googlescholar</a></li>
        </ul>
    </div>
</div>

### Overview

Research in the lab involves the development of statistical models to answer biological questions, balancing biological interpretability, theoretical guarantees, and computational tractability. In particular, we deal with modern big data which is highly interconnected through graphical structures: phylogenetic networks to study evolution, interaction networks to study microbial communities in soil and plants, neural networks to predict phenotypes from genotypes.  

Our work produces a collection of new statistical methods with solid theoretical guarantees and efficient computational implementations that are adaptable to analyze the complex characteristics of modern big biological data.

#### <a name="phylogenomics"></a>Statistical phylogenomics

The Tree of Life is the graphical structure that represents the evolutionary process
from single-cell organisms at the origin of life to the vast biodiversity we see today.
Reconstructing this tree from genomic sequences is challenging due to the variety
of biological forces that shape the signal in the data which constantly push the boundaries of statistical models. In addition, the big data reality can make inference methods obsolete due to their lack of scalability.

In this lab, we work to produce novel statistical models and methods to reconstruct the Tree of Life that are theoretically sound yet computationally efficient and scalable to meet the ever-growing needs of biological bit data. We strive to accompany our theoretical work with open-source publicly available [software](https://solislemuslab.github.io//pages/software.html).

Examples of our current research involve:
- extension of phylogenetic network inference methods to broader classes of networks 
- robustness of phylogenetic inference to microbial datasets like bacteria and viruses
- alternative sampling scheme to MCMC that is expected to produce more efficient bayesian phylogenetic estimation
- statistical properties of [BHV space](https://www.sciencedirect.com/science/article/pii/S0196885801907596) and possible extension to networks

Our work is not purely methodological. Among our current collaborations, we can highlight:
- studying the ancestral protein sequences of _Potyvirus_ and _Picornavirus_
- reconstructing phylogenetic trees and networks and comparative methods to study the evolution of traits related to climate resistance on grapes and carrots
- reconstructing phylogenetic trees and networks and comparative methods to study the evolution of vesicular shapes on _Escovopsis_

We do not live in a statistical bubble! We always welcome new collaborations that can help our research to be relevant and applied to real-life data.


#### <a name="genomics"></a>Statistical genomics

One area of statistical genomics has focused on elucidating ties between genes and diseases (human diseases or plant diseases). Standard analytic methods typically consist of a regression of an individual SNP or genes on a phenotype, but these analyses face numerous challenges including small individual SNP effects, low power due to improper modeling of linkage disequilibrium (LD) patterns, and potential type-I error inflation due to unmodeled population structure or kinship. Furthermore, typical approaches involve single regression models followed by multiple test corrections, thus yielding very stringent cutoffs for significance so that very few SNPs are found to be associated with the phenotype. 

In this lab, we work to produce novel methodologies that are centered on high-dimensional statistical models like penalized regression and post selection inference that can simultaneously model all genes across the genome. Our work incorporates multiple layers of correlations due to relatedness, inbreeding, population structure, spatial structure, or interacting components.

Examples of our research involve:
- post selection inference and penalized regression models applied to GWAS on human disease
- high dimensional models for the integration of different omics data types applied to human microbiome research and plant microbiome reseach

We always welcome new collaborations that can help our research to be relevant and applied to real-life data.

#### <a name="dl"></a>Statistical view in deep learning

intro paragraph

examples of research
- robustness of NN on microbial datasets
- connections of statistical concepts of uncertainty on nn

examples of collaborations:
- tim and sam
- mycovirus

#### <a name="microbiome"></a>Statistics in microbiome research

intro paragraph

examples of research
- spatial correlations ising model
- metagenomes with daniel

examples of collaborations
- potato microbiome
- human microbiome (sam)

### <a name="publications"></a>Publications

#### 2020

Guerrero, V. and C. Sol&iacute;s-Lemus. 2020. A generalized measure of relative dispersion, [Stat. and Prob. Letters](https://www.sciencedirect.com/science/article/pii/S0167715220301097?dgcid=author)

Sol&iacute;s-Lemus, C., S. T. Fischer, A. Todor, C. Liu, E. J. Leslie, D. J. Cutler, D. Ghosh and M. P. Epstein. 2020. Leveraging Family History in Case-Control Analyses of Rare Variation.
[GENETICS](https://doi.org/10.1534/genetics.119.302846)

M. Su, J. Lyles, R. A. Petit III, J. M. Peterson, M. Hargita, H .Tang, C. Sol&iacute;s-Lemus, C. Quave, T. D. Read. 2020. Genomic analysis of variability in delta-toxin levels between Staphylococcus aureus strains. [PeerJ](https://peerj.com/articles/8717/)

#### 2019

Sol&iacute;s-Lemus, C., Ma, X., Hostetter II, M., Kundu, S., Qiu, P., Pimentel-Alarc&oacute;n D., 2019. Prediction of functional markers of mass cytometry data via deep learning. Biostatistics and Bioinformatics, [Springer](https://link.springer.com/chapter/10.1007/978-3-030-33416-1_5).

#### 2018

Sol&iacute;s-Lemus, C., Pimentel-Alarc&oacute;n D., 2018. Breaking the Limits of Subspace Inference. [56th Annual Allerton Conference on
Communication, Control, and Computing](http://allerton.csl.illinois.edu/)

Spooner, D.M., Ruess, H., Arbizu, C.I., Rodriguez, F., Sol&iacute;s-Lemus. 2018. Greatly reduced phylogenetic structure in the cultivated potato clade (Solanum section Petota pro parte). [American Journal of Botany](http://onlinelibrary.wiley.com/doi/10.1002/ajb2.1008/abstract)

Bastide, P., Sol&iacute;s-Lemus, C., Kriebel, R., Sparks, K.W., An&eacute;, C. 2018. Phylogenetic Comparative Methods on Phylogenetic Networks with Reticulations. [bioRxiv](https://www.biorxiv.org/content/early/2017/09/28/194050) [Syst Bio](https://academic.oup.com/sysbio/advance-article/doi/10.1093/sysbio/syy033/4985806?guestAccessKey=507189f8-9ff2-4e12-b17e-29c2a1b2e7ec)

#### 2017

Sol&iacute;s-Lemus, C., Bastide, P., An&eacute;, C. 2017. PhyloNetworks: a package for phylogenetic networks. [Molecular Biology and Evolution](https://academic.oup.com/mbe/article/34/12/3292/4103410?guestAccessKey=1d2c94f2-f064-42ae-a652-ce14cd095442)

An&eacute;, C., Bastide, P., Mariadassou, M., Robin, S., Sol&iacute;s-Lemus C. 2017. Processus d'&eacute;volution r&eacute;ticul&eacute;e: tests de signal phylog&eacute;n&eacute;tique. [Journ&eacute;es de Statistique](http://jds2017.sfds.asso.fr/program/Soumissions/subm211.pdf)

Pimentel-Alarc&oacute;n D., Biswas A., C. Sol&iacute;s-Lemus. 2017.Adversarial Principal Component Analysis. IEEE International Symposium on Information Theory (ISIT) [![pdf (653k)](icons16/pdf-icon.png)](https://danielpimentel.github.io/publications.html).

#### 2016

Sol&iacute;s-Lemus, C., An&eacute;, C. 2016. Inferring phylogenetic networks with maximum pseudolikelihood under incomplete lineage sorting.
[PLoS Genetics](http://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1005896),
[arxiv](http://arxiv.org/abs/1509.06075)

Sol&iacute;s-Lemus, C., Yang, M., An&eacute;, C. 2016. Inconsistency of species-tree methods under gene flow.
[Systematic Biology](http://sysbio.oxfordjournals.org/content/early/2016/05/04/sysbio.syw030.full.pdf?keytype=ref&ijkey=4YgLuAtchHF4QmS)

Baum, D., An&eacute;, C., Larget, B., Sol&iacute;s-Lemus, C., Ho, L.S.T, Boone, P., Drummond, C., Bontrager, M., Hunter, S., Saucier, B. 2016. Statistical evidence for common ancestry: application to primates, [Evolution](http://onlinelibrary.wiley.com/doi/10.1111/evo.12934/abstract)

Pimentel-Alarc&oacute;n D., C. Sol&iacute;s-Lemus. 2016. Crime detection via crowdsourcing. 8th Mexican Conference on Pattern Recognition, Springer International [![pdf (653k)](icons16/pdf-icon.png)](https://danielpimentel.github.io/publications.html).

#### 2015

Sol&iacute;s-Lemus, C., L.L. Knowles and C. An&eacute;. 2015. Bayesian species delimitation combining multiple genes and traits in a unified framework. [Evolution](http://onlinelibrary.wiley.com/doi/10.1111/evo.12582/abstract)

Sol&iacute;s-Lemus, C. (2015). Statistical methods to infer population structure with coalescence and gene flow.  PhD dissertation, Department of Statistics,
University of Wisconsin-Madison
[![pdf (653k)](icons16/pdf-icon.png)](https://www.stat.wisc.edu/~claudia/thesis.pdf)