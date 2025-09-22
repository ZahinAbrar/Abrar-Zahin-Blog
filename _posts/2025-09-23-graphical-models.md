---
title: "Notes on Graphical Models"
layout: single
categories: [intro]
tags: [hello, math]
mathjax: true
---

A tiny test post to verify that math renders correctly.

**Inline math:** $ \Theta_{ij} = 0 \iff X_i \perp X_j \mid X_{\setminus\{i,j\}} $.

**Block math:**

$$
\mathcal{L}(\Theta)
= \log\det(\Theta) - \mathrm{tr}(S\Theta)
\quad\text{with}\quad
\Theta \succ 0
$$

**Another display:**

$$
\arg\min_{\Theta \succ 0}\; -\log\det(\Theta) + \mathrm{tr}(S\Theta) + \lambda \lVert \Theta \rVert_{1}.
$$
