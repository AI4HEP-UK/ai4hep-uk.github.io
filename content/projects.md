---
title: "Projects"
date: 2026-03-02T13:34:30+01:00
draft: false
---

##### AI Inference as a Service deployment at a WLCG Tier-2

_Proponents, University of Glasgow: David Britton_

The objective is to establish an inference-as-a-service platform in a WLCG Tier-2 environment to compare the performance, efficiency, and cost of CPU- and GPU-based infrastructures. The project will identify job scheduling and infrastructure strategies to minimise idle time, maximise value for money, reduce carbon footprint, and assess operational overhead. This benchmarking will provide insights into resource utilisation, informing future large-scale deployments.
An on-Grid inference service demonstrator will be deployed at the Glasgow WLCG Tier-2, leveraging local GPUs and the NVIDIA Triton Inference Server. It will be integrated with standard WLCG middleware and services, including ARC-CE, HTCondor, CVMFS, and XCache. The demonstrator will utilise the ATLAS software framework, Athena, together with Triton, to enable robust and production-ready deployment of machine learning models within the existing experiment environment.
The project will determine the most cost-effective hardware configurations for varying batch sizes and workload profiles, improving both throughput and efficiency of inference tasks. By systematically analysing performance, scalability, and operational trade-offs, the results will directly inform future strategies. Ultimately, this work will provide an evidence-based foundation for scaling machine learning inference services across WLCG, supporting future experimental demands while maintaining efficiency, sustainability, and operational reliability.

Topic: AI for data-intensive analysis, reconstruction, or inference;  AI-enabled operations, monitoring, or infrastructure support; Development of application of methods or tools that can be reused across experiments or institutions.

##### AI-enhanced 2D to 3D pattern recognition in LArTPCs

_Proponents, Lancaster University: Dominic Brailsford_

Pandora is the cornerstone pattern-recognition used for LArTPC reconstruction in DUNE and has a rich history in previous LArTPC neutrino experiments. It marries optimised traditional reconstruction with modern AI, seeing recent performance gains using transformer-based models for 2D shower clustering. Further gains are limited by downstream reconstruction, particularly the 2D–>3D matching across wire planes, where 2D clusters turn into 3D showers; a difficult task due to shape complexity that frustrates procedures relying on matching information between the 2D views.
This project will investigate AI-enhancements to Pandora's 2D→3D shower matching. The 2D→3D matching problem is driven by matching complex features according to their timing profile, involving significant combinatorics due to event complexity. This is suited to AI techniques that can handle high multiplicities and tease out features but has not previously been explored in the LArTPC landscape. The project will setup and benchmark a model to augment the 2D->3D matching, with the ultimate goal of improving shower reconstruction quality whilst maintaining processing efficiency.
Given UK’s strong involvement in DUNE's LArTPC reconstruction development, this work represents a targeted step towards deep AI integration in core reconstruction. The outcome will be a new AI-augmented reconstruction algorithm and performance evaluation, leading to a clear improvement in DUNE’s reconstruction and physics sensitivities. 

Topic: Development of application of methods or tools that can be reused across experiments or institutions.

##### PHAZE-1: Validating Early Predictive Sufficiency for Low-Latency Foundation Models

_Proponents, University of Manchester: Caterina Doglioni, Pratik Jawahar_

We propose developing algorithmic foundations for PHAZE: Probabilistic Hashing And zkMLbased Early-exit, a novel framework for nanosecond-scale inference recently accepted at NeurIPS ML4PS 2025 (<https://arxiv.org/abs/2511.12592>). While Foundation Models (FMs) excel at classifying HEP data, they're too slow for Level-1 triggers. Existing acceleration includes hardware optimization (quantization, pruning for FPGAs) and model compression (knowledge distillation). Early Exit (EE)—predicting outputs from initial layers only—remains underexplored in HEP. Unlike other methods limited by hardware constraints, EE can exploit arbitrarily complex models if the acceleration-performance trade-off (Early Predictive Sufficiency) is acceptable. This project quantifies Early Predictive Sufficiency by studying "inference speedup vs. performance loss" for large-scale HEP-ML models. We'll build a benchmarking framework analyzing particle physics models (ParticleNet, ParticleNext, ParT, GN2) using EE strategies to identify the earliest latent layers reliably proxying full model decisions at L1 trigger latency constraints. We'll also analyze extracting fixed-size, quantizable activation vectors for PHAZE's cryptographic steps. Our main deliverable will be quantified accuracy-latency trade-off, which will benefit the broader community that uses these models for real-time applications and motivate further EE research for HEP inference acceleration.

Topic: Fast, resource-efficient ML for real-time or near-real-time applications.

##### Smart Monitoring: AI-Driven Analysis of Distributed Systems

_Proponents, University of Liverpool: Rob Fay, Monica D’Onofrio, Eduardo Rodrigues_

AI models offer the potential for enhancing detection and analysis of issues through monitoring frameworks. By connecting Zabbix (an open-source monitoring platform - <https://www.zabbix.com/> ) to a locally run AI model through a MCP (Model Context Protocol) framework, we can extend the AI model to query, interactively or automatically, the state of the monitored systems and services, enabling dynamic detection and complex analysis. This model could also further be expanded with additional tools to enable further interactive investigation and expanded analysis based on data from other sources (e.g. direct host querying, log analysis, external monitoring). The model also has the scope to carry out autonomous actions to respond to and address detected issues, given appropriate tools and the appropriate caution. We will assess the current viability of this approach with regard to monitoring of LHC-related computing operations, initially implementing a proof-of-concept demonstrator, and subsequently refining this to assess the scope for improving performance and efficiency with different AI models and hardware constraints.

##### Pandora Deep Learning for Interaction Vertex Reconstruction in SBND

_Proponents, University of Sheffield: Alexandra Moor, Rhiannon Smith-Jones_

This project aims to improve pattern recognition in Liquid Argon (LAr) neutrino detectors by the use of Deep Learning in the area of vertexing. Finding the interaction vertex of the neutrino is a key step upon which the rest of the reconstruction is built, and is often difficult to attain precisely due to the abundance of activity that surrounds each vertex. This work is being completed within the context of Pandora, a well established multi-algorithm pattern recognition software used across all active LAr Time Projection Chamber-based neutrino experiments. The algorithm being adapted was originally developed for the Deep Underground Neutrino Experiment (DUNE) by Andy Chappell and showed extremely promising results, which we expect to continue in further LAr experiments investigated.
It takes a two pass approach, first identifying a general region of interest before performing a more detailed analysis using those results.
In DUNE, this provided a notable improvement in performance over the Boosted Decision Tree which was used previously to accomplish the vertexing (<https://doi.org/10.1140/epjc/s10052-025-14313-8>).
    
