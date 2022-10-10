---
title: Analyse différentielle d’expression de gènes
author: ''
date: '2022-09-30'
slug: newrnaseq
categories: []
tags: [rnaseq]
---

La prochaine animation du groupe de travail StatOmique, soutenu par le gdr BioInformatique Moléculaire,
aura lieu le **mardi 25 octobre** sur le nouveau campus Agro Paris-Saclay, 22 place de l'Agronomie à Palaiseau (coordonnées GPS: 48.71401 2.1964).

Plus d'infos pour venir sur le campus depuis le site de l'école [ici](https://www.agroparistech.fr/venir-lecole)

### Programme

- 10h Accueil

- 10h30 Introduction et tour de table

- 10h45 **Benchmark of Differential Gene Expression Analysis Methods for Inter-species RNA-Seq Data using a Phylogenetic Simulation Framework** , Paul Bastide, IMAG – UMR 5149

Abstract : 

Inter-species RNA-Seq datasets are increasingly common, and have the potential to answer new questions on gene expression patterns across the evolution. Single species differential expression analysis is a now well studied problem, that benefits from sound statistical methods. Extensive reviews on biological or synthetic datasets have provided the community with a clear picture on the relative performances of the available tools in various settings. Such benchmarks are still missing in the inter-species gene expression context. In this work, we take a first step in this direction by developing and implementing a new simulation framework. This tool builds on both the RNA-Seq and the Phylogenetic Comparative Methods literatures to generate realistic count datasets, while taking into account the phylogenetic relationships between the samples. We illustrate the features of this new framework through a targeted simulation study, that reveals some of the strengths and weaknesses of both the classical and phylogenetic approaches for inter-species differential expression analysis. The tool has been integrated in the R package `compcodeR` freely available on Bioconductor.

- 11h45 [**ABEILLE: a novel method for ABerrant Expression Identification empLoying machine Learning from RNA-sequencing data.**](../../../../media/StatOmique2022-ABEILLE.pdf) Justine Labory, Medical Data Laboratory, Université Côte d’Azur

- 12:10 [**Robust deconvolution of transcriptomic samples using the gene covariance structure.**](../../../../media/StatOmique2022-BChassagnol.pdf) Bastien Chassagnol, Sorbonne Université, LPSM // Les Laboratoires Servier 

- Pause déjeuner

- 13:45 **Analyse de cribles génétiques CRISPR-Cas9.** Pierre Gestraud, Institut Curie

Résumé: 
Les screens CRISPR-Cas9 permettent l’interrogation de la fonction des gènes à grande échelle. Des perturbations génétiques sont introduites dans des pools de cellules qui sont ensuite soumises à une pression de sélection (compétition cellulaire, traitement, infection virale...). Les effets de ces perturbations sont ensuite évalués par séquençage des guide RNA spécifiques de chaque gène. L’analyse de ce type de données soulève plusieurs questions à cause des caractéristiques de l’expérience (notamment la présence de plusieurs guides par gènes). Après présentation de la technologie et de ses buts nous verrons le workflow d’analyse mis en place : comptage, analyse au niveau guide RNA et agrégation au niveau gène.

- 14:45 [**Differential Analysis for RNA-seq using Intensive Randomization.**](../../../../media/StatOmique2022-DDesaulle.pdf) Dorota Delasaulle, UR 7537 Biostatistique, Traitement et Modélisation des données biologiques, Fac. de Pharmacie, Univ. Paris Cité

- 15:15 Pause

- 15:30 **Neglecting normalization impact in semi-synthetic RNA-seq data simulation generates artificial false positives.** Boris Hejblum Inserm U1219 Bordeaux Population Health, Inria BSO, Université de Bordeaux

Abstract :

By reproducing differential expression analysis simulation results presented by Li et al, we identified a caveat in the data generation process. Data not truly generated under the null hypothesis led to incorrect comparisons of benchmark methods. We provide corrected simulation results that demonstrate the good performance of dearseq and argue against the superiority of the Wilcoxon rank-sum test as suggested by Li et al. 

- 16:30 Discussion échange autour des pratiques de l'analyse différentielle d'expression de gènes

- 17:00 Clôture de la journée

#### Quelques références

Bastide, P., Soneson, C., Lespinet, O., Gallopin, M. **Benchmark of Differential Gene Expression Analysis Methods for Inter-species RNA-Seq Data using a Phylogenetic Simulation Framework.** [bioarvix:2022.01.21.476612](https://www.biorxiv.org/content/10.1101/2022.01.21.476612v1)

**compcodeR** 
Soneson C (2014). **compcodeR - an R package for benchmarking differential expression methods for RNA-seq data.** _Bioinformatics_, 30(17), 2517-2518.


Hejblum, B., Ba, K., Thiébaut, R. , Agniel, D. **Neglecting normalization impact in semi-synthetic RNA-seq data simulation generates artificial false positives.** [biorxiv:2022.05.10.490529](https://www.biorxiv.org/content/10.1101/2022.05.10.490529v1.full.pdf)  

Li, Y., Ge, X., Peng, F. et al. **Exaggerated false positives by popular differential expression methods when analyzing human population samples.** _Genome Biology_, 79, 23 (2022). [doi.org/10.1186/s13059-022-02648-4](https://doi.org/10.1186/s13059-022-02648-4)
