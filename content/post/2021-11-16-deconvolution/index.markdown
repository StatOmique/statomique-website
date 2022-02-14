---
title: Sélection de variables et méthodes de déconvolution
author: ''
date: '2021-11-16'
slug: deconvolution
categories: []
tags: []
---

### Programme de la journée

- 9h30 Accueil café  

- 10h **A variable selection approach for highly correlated predictors in high-dimensional data**
Wencan Zhu (UMR MIA-Paris, AgroParisTech, INRAE – Université Paris-Saclay, Sanofi R&D)

Résumé : In genomic studies, identifying biomarkers associated with a variable of interest is a major
concern in biomedical research. Regularized approaches are classically used to performvariable selection
in high-dimensional linear models. However, these methods can fail in highly correlated settings.  
Results: We propose a novel variable selection approach called WLasso, taking these correlations into
account. It consists in rewriting the initial high-dimensional linear model to remove the correlation between the biomarkers (predictors) and in applying the generalized Lasso criterion. The performance of WLasso is assessed using synthetic data in several scenarios and compared with recent alternative approaches. The results show that when the biomarkers are highly correlated, WLasso outperforms the other approaches in sparse high-dimensional frameworks.

- 11h **Comparaison de méthodes de déconvolution de bulk RNA-Seq pour l'étude de l'infection par la fièvre Lassa**
Emeline Perthame (Hub de Bioinformatique et Biostatistique, Institut Pasteur), en collaboration avec Natalia Pietrosemoli et Hélène Lopez-Maestre (Hub de Bioinformatique et Biostatistique, Institut Pasteur) et Sylvain Baize (PI de l'unité de Biologie des infections virales émergentes, Institut Pasteur)

Résumé : On s'intéresse à un [jeu de données transcriptomiques dans lequel la cinétique d'infection par la fièvre Lassa est étudiée](doi.org/10.1038/s42003-020-01543-7). Les chercheurs s'intéressent à la comparaison de la pénétrance du virus dans différents tissus et organes. En particulier, ils s'intéressent à l'inférence des proportions de types cellulaires pour différentes souches du virus. Dans cet exposé, nous présenterons brièvement les données et leur plan d'expériences, puis nous présenterons une comparaison des différentes méthodes de déconvolution que nous avons appliquées (dont CIBERSORT, méthode vraisemblablement la plus connue/utilisée) et enfin des éléments d'interprétation des résultats de ces analyses. Nous verrons notamment que la méthode de normalisation des comptages, ainsi que la qualité de la matrice de signature caractérisant les types cellulaires ont un impact considérable sur les résultats.  
                                                                                                           - 12-13h30 Pause déjeuner   
                                                                                                                                                                                                                      - 13h30 **Medepir - un guide pour la déconvolution non-supervisée de données de méthylation de l'ADN**
Clémentine Decamps (TIMC-IMAG, UMR 5525, Univ. Grenoble Alpes, CNRS)   

Résumé : En partant du constat qu'il n'existait pas dans la littérature de benchmark de ces méthodes, nous nous sommes lancés dans leur comparaison, et dans l'évaluation de l'intérêt du pré-traitement des données à travers un "data challenge" organisé en 2018. Des suites de ce travail, nous avons tiré un package, Medepir, regroupant les connaissances acquises sur des jeux de simulations. Au-delà de la problématique initiale, se pose ensuite la question du benchmarking des méthodes de déconvolution en général, de la reproductibilité et de l'intégration des nouveaux jeux de données / méthodes.  
                                                                                                           - 14h30 **Retour d'expérience sur l’utilisation de l’algorithme CIBERSORT pour l’estimation de l’abondance de populations cellulaires à partir de données transcriptomiques**
Boris Hejblum (Inserm U1219 Bordeaux Population Health, Inria BSO, Université de Bordeaux)

Résumé : Application de Cibersort dans le cadre d'un essai clinique (COVERAGE Immuno) de suivi de patients COVID où nous disposons à la fois de données de transcriptomiques et de données de populations cellulaires. 

#### Quelques références

**WLasso:** [package R WLasso](cran.r-project.org/package=WLasso/)  
W. Zhu, C. Levy-Leduc, N. Ternes. **A variable selection approach for highly correlated predictors
in high-dimensional genomic data.** [arXiv:2007.10768](arXiv:2007.10768)  

**Medepir::** [package R medepir](github.com/bcm-uga/medepir)  
Decamps, C., Privé, F., Bacher, R. et al. **Guidelines for cell-type heterogeneity quantification based on a comparative analysis of reference-free DNA methylation deconvolution software.** _BMC Bioinformatics_ 21, 16 (2020). [doi.org/10.1186/s12859-019-3307-2](doi.org/10.1186/s12859-019-3307-2)

Baillet, N., Reynard, S., Perthame, E. et al. Systemic viral spreading and defective host responses are associated with fatal Lassa fever in macaques. Commun Biol 4, 27 (2021). [doi.org/10.1038/s42003-020-01543-7](doi.org/10.1038/s42003-020-01543-7)  
Shen-Orr, S., Tibshirani, R., Khatri, P. et al. **Cell type–specific gene expression differences in complex tissues.** _Nat Methods_ 7, 287–289 (2010). [doi.org/10.1038/nmeth.1439](doi.org/10.1038/nmeth.1439)  
doi.org/10.1038/nmeth.1439  
**Cibersort:**
Newman, A.M., Steen, C.B., Liu, C.L. et al. **Determining cell type abundance and expression from bulk tissues with digital cytometry.** _Nat Biotechnol_ 37, 773–782 (2019). [doi.org/10.1038/s41587-019-0114-2](doi.org/10.1038/s41587-019-0114-2)


                                                                                             
                                                                                             
