---
layout: distill
title: "Ch:0 Introduction"
date: 2025-02-09
private: false
tags: [SDE101]
# Anonymize when submitting

authors:
  - name: Maitreya Patel
    url: "https://maitreyapatel.com/"
    affiliations:
      name: Arizona State University

# Below is an example of injecting additional post-specific styles.
# This is used in the 'Layouts' section of this post.
# If you use this post as a template, delete this _styles block.
_styles: >
  .fake-img {
    background: #bbb;
    border: 1px solid rgba(0, 0, 0, 0.1);
    box-shadow: 0 0px 4px rgba(0, 0, 0, 0.1);
    margin-bottom: 12px;
  }
  .fake-img p {
    font-family: monospace;
    color: white;
    text-align: left;
    margin: 12px 0;
    text-align: center;
    font-size: 16px;
  }
---


In the realm of generative models, diffusion and flow models have rapidly emerged as transformative tools across fields. Yet, beneath their impressive applications lies a rich, often concealed, mathematical foundation—a foundation built upon stochastic processes, probability theory, and differential equations. This series is an invitation to journey beneath the surface and explore the core principles that have made these models possible.

_The Stochastic Journey_ is conceived as a live, evolving series dedicated to unraveling the elegant mathematics that underpin recent advances in visual generative models. Rather than merely explaining how these models work mathematically, the focus here is to trace their lineage back to the foundational theories of stochastic calculus—delving into the origins of ideas like Brownian motion, Kolmogorov's continuity theorem, and stochastic differential equations (SDEs). As the series progresses, each post will introduce key derivations and insights, gradually constructing a clear, intuitive, and rigorous picture of the mathematical landscape that informs modern generative techniques.

It is all too common today to master the application of diffusion models without fully understanding the deep mathematical evolution that brought us to this moment. While many practitioners can skillfully implement these models, the intricate journey—from abstract theorems and classical proofs to the practical algorithms used in contemporary research—remains largely uncharted territory for most. This series aims to bridge that gap, revealing the profound insights that underpin our current tools and highlighting the evolution of ideas that have enabled today's breakthroughs.

A central reference for this exploration is [Stochastic Differential Equations: An Introduction with Applications by Bernt Øksendal](https://link.springer.com/book/10.1007/978-3-642-14394-6)—a seminal text that provides deep insights into SDEs. Recognizing that Øksendal's work can be challenging for those without an extensive mathematical background, this series is crafted to demystify complex ideas through detailed explanations and derivations. It is designed specifically for readers who may have a mathematical familiarity with diffusion models but seek a deeper understanding of the mathematical journey behind them.

This work does not assume advanced prior knowledge of stochastic calculus or differential equations; instead, it is tailored for anyone eager to uncover the mathematics that paved the way for modern generative modeling. As new insights and derivations emerge, they will be shared in real time as part of this ongoing, live series. The goal is not to provide a definitive guide to diffusion or flow models, but to peel back the layers and illuminate the historical context that has led us to this technological frontier.

Welcome to _The Stochastic Journey_. Join me as we explore the rich mathematical heritage that made these advances possible. Enjoy the exploration!