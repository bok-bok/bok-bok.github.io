---
title: "What Variables Affect Out-Of-Distribution Generalization in Pretrained Models?"
collection: publications
category: preprints
# permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'Md Yousuf Harun<sup>\*</sup>, <b>Kyungbok Lee<sup>\*</sup></b>, Jhair Gallardo,  
Giri Krishnan, Christopher Kanan'
date: 2024-09-25
venue: 'Neurips, 2024'

paperurl: 'https://arxiv.org/pdf/2405.15018'
---
Embeddings produced by pre-trained deep neural networks (DNNs) are widely
used; however, their efficacy for downstream tasks can vary widely. We study the
factors influencing out-of-distribution (OOD) generalization of pre-trained DNN
embeddings through the lens of the tunnel effect hypothesis, which suggests deeper
DNN layers compress representations and hinder OOD performance. Contrary
to earlier work, we find the tunnel effect is not universal. Based on 10,584 linear
probes, we study the conditions that mitigate the tunnel effect by varying DNN
architecture, training dataset, image resolution, and augmentations. We quantify
each variable’s impact using a novel SHAP analysis. Our results emphasize the
danger of generalizing findings from toy datasets to broader contexts.