---
title:          "Trification: A Comprehensive Tree-based Strategy Planner and Structural Verification for Fact-Checking"
date:           2025-11-29
selected:       true
tags:           ["# fact-checking", "# LLM agents", "# graph reasoning"]
pub_post:       'Under review.'

abstract: >-
  Technological advancement allows information to be shared in just a single click, which has enabled the rapid spread of false information. This makes automated fact-checking system necessary to ensure the safety and integrity of our online media ecosystem. Previous methods have demonstrated the effectiveness of decomposing the claim into simpler sub-tasks and utilizing LLM-based multi agent system to execute them. However, those models faces two limitations: they often fail to verify every component in the claim and lack of structured framework to logically connect the results of sub-tasks for a final prediction. In this work, we propose a novel automated fact-checking framework called Trification. Our framework begins by generating a comprehensive set of verification actions to ensure complete coverage of the claim. It then structured these actions into a dependency graph to model the logical interaction between actions. Furthermore, the graph can be dynamically modified, allowing the system to adapt its verification strategy. Experimental results on two challenging benchmarks demonstrate that our framework significantly enhances fact-checking accuracy, thereby advancing current state-of-the-art in automated fact-checking system.
cover:          /assets/images/covers/Trification_resized.png
authors:
  - Anab Maulana Barik
  - Shou Ziyi
  - Yang Kaiwen
  - Yang Qi
  - Shen Xin#
links:
  Paper: https://arxiv.org/abs/2512.00267
---