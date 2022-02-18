---
title: 'Eventer: Software you can train to detect spontaneous synaptic responses for you, BNA 2021 Poster'
date: 2021-01-01
authors: ['Winchester, G.', 'Liu, S.', 'Steele, O.G.', 'Chagas, A.M.', 'Aziz, W.','Penn, A.C. ']
layout: post
categories: []
tags: []
published: true
summary: Detection and analysis of spontaneous synaptic events is an extremely common task in many neuroscience research labs. Various algorithms and tools have been developed over the years to improve the sensitivity for detecting synaptic events. However, the final stages of most procedures for detecting synaptic events still involves manual selection of candidate events. This step in the analysis is laborious and requires care and attention to maintain consistency of event selection across the whole dataset. Manual selection can introduce bias and subjective selection criteria that cannot be shared with other labs simply in reporting methods. To address this, we have created Eventer ...
---  

<center>  

<h1 style="font-size:10"> 

**BNA 2021 Poster**    
*[Download PDF](Eventer_BNA_2021.pdf)*  

</h1>
</center>  
  
  
## Title:
Eventer: Software you can train to detect spontaneous synaptic responses for you
## DOI:
BNA 2021 Festival of Neuroscience Poster abstracts. *Brain and Neuroscience Advances*. January 2021. doi:[10.1177/23982128211035062](https://doi.org/10.1177/23982128211035062)  

## Abstract:
Detection and analysis of spontaneous synaptic events is an extremely common task in many neuroscience research labs. Various algorithms and tools have been developed over the years to improve the sensitivity for detecting synaptic events. However, the final stages of most procedures for detecting synaptic events still involves manual selection of candidate events. This step in the analysis is laborious and requires care and attention to maintain consistency of event selection across the whole dataset. Manual selection can introduce bias and subjective selection criteria that cannot be shared with other labs simply in reporting methods. To address this, we have created Eventer, a standalone application for the detection of spontaneous synaptic events acquired by electrophysiology or imaging. This opensource application uses the freely available MATLAB Runtime and can be deployed on Mac, Windows and Linux systems. The principle of the Eventer application is to learn the user’s ‘expert’ strategy for classifying a set of detected event candidates from a small subset of the data, and then automatically apply the same criterion on the whole dataset. Eventer uses a suitable model template to pull out event candidates using fast fourier transform (FFT)-based deconvolution. Random Forests are then trained to associate various features of the events with manual classification. The stored model file can be reloaded and used to analyse large datasets with greater consistency. The eventer website (https://eventerneuro.netlify.app/) includes a repository where researchers can upload and share their machine learning model files and thereby provide greater opportunities for enhancing reproducibility when analysing datasets of spontaneous synaptic activity. In summary, Eventer, and the associated repository, could allow researchers studying synaptic transmission to increase throughput of their data analysis and address the increasing concerns of reproducibility in neuroscience research.

***
This post was automatically generated by
Team Eventer Admin  
***