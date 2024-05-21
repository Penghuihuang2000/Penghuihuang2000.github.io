---
title: "Accurate estimation of rare cell-type fractions from tissue omics data via hierarchical deconvolution"
collection: publications
permalink: /publication/HiDecon
date: June 2024
venue: 'Annals of Applied Statistics'
paperurl: "https://projecteuclid.org/journals/annals-of-applied-statistics/volume-18/issue-2/Accurate-estimation-of-rare-cell-type-fractions-from-tissue-omics/10.1214/23-AOAS1829.full"
---

Many existing deconvolution methods have difficulties estimating highly correlated or rare cell types. To address this challenge, hierarchical deconvolution (HiDecon) uses single-cell RNA sequencing references and a hierarchical cell-type tree, which models the similarities among cell types and cell differentiation relationships, to estimate cellular fractions in bulk data. By coordinating cell fractions across layers of the hierarchical tree, cellular fraction information is passed up and down the tree, which helps correct estimation biases by pooling information across related cell types.
[Download R package here](https://github.com/randel/HiDecon)
