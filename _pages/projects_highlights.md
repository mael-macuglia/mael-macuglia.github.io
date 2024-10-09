---
layout: archive
title: "Projects & Highlights"
permalink: /projects-highlights/
author_profile: false
---

## Research Projects:







<div style="max-width: 800px; margin: 20px auto; font-family: Arial, sans-serif; background-color: #f9f9f9; border: 1px solid #e0e0e0; border-radius: 8px; padding: 20px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  <h3 style="color: #333; margin-top: 0; margin-bottom: 5px;">
    Mini-Batching Theory: Matrix Product Concentration Methods
    <a href="/files/msc_thesis.pdf" target="_blank" style="font-size: 0.7em; color: #0066cc; text-decoration: none; margin-left: 10px;">[pdf]</a>
  </h3>
  <p><em>Supervisor:</em> Prof Afonso Bandeira</p>
  
  <details>
    <summary style="cursor: pointer; color: #0066cc; font-weight: bold; margin-bottom: 10px;">Click to view abstract</summary>
    <div style="padding: 15px; background-color: #ffffff; border-radius: 5px; border: 1px solid #e0e0e0;">
      <p>In modern data science and machine learning, particularly for large-scale problems, optimization plays a crucial role. Mini-batching has emerged as a practical approach, yet its theoretical underpinnings remain incompletely understood. This work aims to bridge this gap by providing rigorous theoretical analysis of mini-batch stochastic gradient descent (SGD) methods.</p>
      
      <p>We prove that mini-batch SGD, applied to consistent least squares problems, converges at the same rate as its deterministic counterpart, given a sufficiently large batch size. Our analysis accommodates versatile sampling procedures, encompassing both standard SGD with uniform sampling and averaging Kaczmarz methods.</p>
      
      <p>We provide both expectation and high-probability bounds, leveraging novel concentration results for products of matrices—a departure from traditional optimization proof techniques. Building on Bollapragada et al.'s work [4], which showed expected convergence for mini-batch SGD with heavy ball momentum, we extend their results to provide high-probability bounds under the same conditions.</p>
      
      <p>Additionally, we present expectation bounds for μ-strongly convex and L-smooth functions that closely approximate quadratics, demonstrating that mini-batch SGD in the interpolation regime converges similarly to gradient descent, given an adequately large batch size.</p>
      
      <p>Our results not only advance the theoretical understanding of mini-batching but also offer practical insights for algorithm selection and tuning in large-scale optimization scenarios. By bridging the gap between stochastic and deterministic methods, this work contributes to the foundation of efficient, scalable optimization techniques for modern machine learning applications.</p>
    </div>
  </details>
</div>

## Script & Other Content:



[Your content goes here]