---
title: "Attention Is All You Need — What Still Holds Up"
date: 2026-06-01 10:00:00 +0000
categories: [Paper Notes]
tags: [transformers, attention, nlp]
math: true
---

The 2017 transformer paper is now infrastructure. Here's what's still underappreciated.

## The core idea

$$\text{Attention}(Q, K, V) = \text{softmax}\left(\frac{QK^T}{\sqrt{d_k}}\right)V$$

Every token attends to every other simultaneously — no sequential bottleneck, which is what made scaling possible.

## What holds up

The architecture is remarkably robust across domains: vision, protein folding, code generation. The insight that full-sequence attention beats recurrence has proven universal.
