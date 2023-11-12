---
title: "Mixed Precision Support Vector Machines"
excerpt: "Modified version of the Support Vector Machines optimization problem for targeting low precision posit representation at inference time."
collection: portfolio
---

Real-time or power-constrained applications employ smaller number formats (posits) to result in smaller memory footprints, higher performance, and lower power consumption.
The key task of every efficient implementation is to identify the lowest working precision acceptable to achieve a classification accuracy comparable to a reference implementation in double-precision floating-point arithmetic.
The focus of this project is to realize a modified version of the Support Vector Machine optimization problem, that takes into account the fact that during the inference phase, the model will be executed on devices that use low precision posits.
In particular, the idea of this project is to modify the underlying optimization method during the training phase, modifying the constraints in the dual problem, in order to have better results at inference time with posits.


<a href="https://github.com/terranovafr/MixedPrecisionSVM" style="background-color: blue; color: white; padding: 10px 20px; text-align: center; text-decoration: none; display: inline-block; margin: 10px 5px; cursor: pointer;">Github Project</a>
