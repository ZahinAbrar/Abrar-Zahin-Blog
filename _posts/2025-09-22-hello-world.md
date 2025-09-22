---
title: "Hello, World (with Math)"
categories: [intro]
tags: [hello, math]
layout: single
toc: false
mathjax: true   # enable MathJax on this page (Minimal Mistakes)
---

A tiny test post to verify that math renders correctly.

Inline math example: \\( \Theta_{ij} = 0 \iff X_i \perp X_j \mid X_{\setminus\{i,j\}} \\).

Block math example:

$$
\mathcal{L}(\Theta)
= \log\det(\Theta) - \mathrm{tr}(S\Theta)
\quad\text{with}\quad
\Theta \succ 0
$$

Another display using \\[ ... \\] delimiters:

\\[
\arg\min_{\Theta \succ 0} \; -\log\det(\Theta) + \mathrm{tr}(S\Theta) + \lambda \|\Theta\|_{1}.
\\]

If you can read these formulas on your blog page, MathJax is working ✅

