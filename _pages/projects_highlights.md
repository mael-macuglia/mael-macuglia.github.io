---
layout: archive
title: "Projects & Highlights"
permalink: /projects-highlights/
author_profile: false
---

## Research Projects:





<div style="max-width: 800px; margin: 20px auto; font-family: Arial, sans-serif; background-color: #f9f9f9; border: 1px solid #e0e0e0; border-radius: 8px; padding: 20px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  <h3 style="color: #333; margin-top: 0; margin-bottom: 5px;">
    Uncertainty modeling for fine-tuned implicit functions
    <a href="https://arxiv.org/pdf/2406.12082" target="_blank" style="font-size: 0.7em; color: #0066cc; text-decoration: none; margin-left: 10px;">[pdf]</a>
  </h3>
  <p style="color: #666; margin-top: 5px; margin-bottom: 10px;">(Under review for ICLR 2025)</p>
  <p><em>Supervisor:</em> Dr. Anna Susmelj</p>
  
  <details>
    <summary style="cursor: pointer; color: #0066cc; font-weight: bold; margin-bottom: 10px;">Click to view abstract</summary>
    <div style="padding: 15px; background-color: #ffffff; border-radius: 5px; border: 1px solid #e0e0e0;">
      <p>Implicit functions such as Neural Radiance Fields (NeRFs), occupancy networks, and signed distance functions (SDFs) have become pivotal in computer vision for reconstructing detailed object shapes from sparse views. Achieving optimal performance with these models can be challenging due to the extreme sparsity of inputs and distribution shifts induced by data corruptions. To this end, large, noise-free synthetic datasets can serve as shape priors to help models fill in gaps, but the resulting reconstructions must be approached with caution.</p>

      <p>Uncertainty estimation is crucial for assessing the quality of these reconstructions, particularly in identifying areas where the model is uncertain about the parts it has inferred from the prior. In this paper, we introduce Dropsembles, a novel method for uncertainty estimation in tuned implicit functions.</p>

      <p>We demonstrate the efficacy of our approach through a series of experiments, starting with toy examples and progressing to a real-world scenario. Specifically, we train a Convolutional Occupancy Network on synthetic anatomical data and test it on low-resolution MRI segmentations of the lumbar spine.</p>

      <p>Our results show that Dropsembles achieve the accuracy and calibration levels of deep ensembles but with significantly less computational cost.</p>
    </div>
  </details>
</div>

<div style="max-width: 800px; margin: 20px auto; font-family: Arial, sans-serif; background-color: #f9f9f9; border: 1px solid #e0e0e0; border-radius: 8px; padding: 20px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  <h3 style="color: #333; margin-top: 0; margin-bottom: 5px;">
    Mini-Batching Theory: Matrix Product Concentration Methods
    <a href="/files/msc_thesis.pdf" target="_blank" style="font-size: 0.7em; color: #0066cc; text-decoration: none; margin-left: 10px;">[pdf]</a>
  </h3>
   <p style="color: #666; margin-top: 5px; margin-bottom: 10px;">Msc Thesis: Grade 6/6</p>
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






<div style="max-width: 800px; margin: 20px auto; font-family: Arial, sans-serif; background-color: #f9f9f9; border: 1px solid #e0e0e0; border-radius: 8px; padding: 20px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  <h3 style="color: #333; margin-top: 0; margin-bottom: 5px;">
    Minimax Lower Bounds for Sparse Causal Estimators
    <a href="/files/semester_thesis.pdf" target="_blank" style="font-size: 0.7em; color: #0066cc; text-decoration: none; margin-left: 10px;">[pdf]</a>
  </h3>
  <p><em>Supervisor:</em> Konstantin Donhauser, Statistical Machine Learning Lab</p>
  
  <details>
    <summary style="cursor: pointer; color: #0066cc; font-weight: bold; margin-bottom: 10px;">Click to view Problem Description</summary>
    <div style="padding: 15px; background-color: #ffffff; border-radius: 5px; border: 1px solid #e0e0e0;">
      <p>Assume a data set of patient's covariates (think: blood analysis, symptomatic, etc...) drawn from some population. We give treatment with a certain probability to this population set and we observe the outcome variable on both patient with treatment and without.</p>
      <p>Further assume an estimate of the difference of effects between the two groups (treatment vs no treatment) which is assumed to be <em>sparse</em>.</p>
      <p>The goal is to show a lower bound on any procedure (algorithm) for recovering the support of the difference in treatment effect.</p>
    </div>
  </details>
  
  <p style="margin-top: 15px; font-style: italic; color: #666;">
    Disclaimer: The bounds we found are assumed to be too loose. The problem remains an open problem up to these days (Oct 2024).
  </p>
</div>






## Script & Other Content:


<div style="max-width: 800px; margin: 20px auto; font-family: Arial, sans-serif; background-color: #f9f9f9; border: 1px solid #e0e0e0; border-radius: 8px; padding: 20px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  <h3 style="color: #333; margin-top: 0; margin-bottom: 5px;">
    Numerical Methods for Linear Systems and Least Squares
    <a href="/files/linear_sys_numerics.pdf" target="_blank" style="font-size: 0.7em; color: #0066cc; text-decoration: none; margin-left: 10px;">[pdf]</a>
  </h3>  
  <details>
    <summary style="cursor: pointer; color: #0066cc; font-weight: bold; margin-bottom: 10px;">Click to view Table of Contents</summary>
    <div style="padding: 15px; background-color: #ffffff; border-radius: 5px; border: 1px solid #e0e0e0;">
      <h2>Table of Contents</h2>

      <h3>1. Linear Algebra Review</h3>
      <ul>
        <li>1.1 Vector Spaces</li>
        <li>1.2 Some Matrix Properties/Definitions</li>
        <li>1.3 Eigenvalues and Eigenvectors</li>
        <li>1.4 Similarity Transformations</li>
        <li>1.5 Singular Value Decomposition</li>
        <li>1.6 Inner product, Norms and Metric Spaces</li>
        <li>1.7 Matrix Norm</li>
      </ul>

      <h3>2. Direct Methods for Linear Systems of Equations</h3>
      <ul>
        <li>2.1 Gaussian Elimination Methods and LU Factorization</li>
        <li>2.2 Direct Solvers in Eigen</li>
        <li>2.3 Exploiting Structure when Solving LSE</li>
        <li>2.4 Not Discussed</li>
      </ul>

      <h3>3. Direct Methods for Linear Least Squares</h3>
      <ul>
        <li>3.1 Least Squares Definition and Setup</li>
        <li>3.2 Geometric Interpretation of Least Squares</li>
        <li>3.3 Normal Equation
          <ul>
            <li>3.3.1 Solving the N.EQ</li>
          </ul>
        </li>
        <li>3.4 Orthogonal Transformation for Solving Least Squares Problems
          <ul>
            <li>3.4.1 QR decomposition</li>
            <li>3.4.2 Computation of QR decomposition</li>
            <li>3.4.3 Eigen: QR Decomposition for Solving LS Systems</li>
          </ul>
        </li>
        <li>3.5 Moore-Penrose Pseudoinverse</li>
        <li>3.6 Not Discussed in This Script</li>
      </ul>

      <h3>4. SVD Based Methods for Least Square Problems</h3>
      <ul>
        <li>4.1 SVD for Solving General Least Squares Problems</li>
        <li>4.2 SVD in Eigen</li>
      </ul>
    </div>
  </details>
  <p style="margin-top: 15px; font-style: italic; color: #666;">
    These lecture notes were created for the "NumCSE PVK" (Numerical Methods for CSE) that I taught. This is a condensed block course offered during the summer, just before the exam period.
  </p>
</div>





<div style="max-width: 800px; margin: 20px auto; font-family: Arial, sans-serif; background-color: #f9f9f9; border: 1px solid #e0e0e0; border-radius: 8px; padding: 20px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
<h3 style="color: #333; margin-top: 20px; margin-bottom: 20px;">
  Basics of ML Theory 
  <a href="/files/modelling_of_Ml.pdf" target="_blank" style="font-size: 0.7em; color: #0066cc; text-decoration: none; margin-left: 10px;">[slides pdf]</a>
</h3>  

<h3 style="color: #333; margin-top: 20px; margin-bottom: 5px;">
  Advanced Statistical Theory Notes
  <a href="/files/some_stat_notes.pdf" target="_blank" style="font-size: 0.7em; color: #0066cc; text-decoration: none; margin-left: 10px;">[pdf]</a>
</h3>
  <details>
    <summary style="cursor: pointer; color: #0066cc; font-weight: bold; margin-bottom: 10px;">Click to view Table of Contents</summary>
    <div style="padding: 15px; background-color: #ffffff; border-radius: 5px; border: 1px solid #e0e0e0;">
      <h2>Table of Contents</h2>
      <ol style="padding-left: 20px;">
        <li>Statistical Learning Framework</li>
        <li>Basics of Regression Analysis and Prediction Tasks
          <ul>
            <li>Random Design</li>
            <li>Fixed Design</li>
          </ul>
        </li>
        <li>Theory of Linear Regression
          <ul>
            <li>Multiple Linear Regression in Compact Form</li>
            <li>Multivariate Linear Regression</li>
          </ul>
        </li>
        <li>Theory of Hypothesis Testing
          <ul>
            <li>Modeling the Problem</li>
          </ul>
        </li>
        <li>Statistical Modelling for Linear Regression</li>
      </ol>
    </div>
  </details>

  <h3 style="color: #333; margin-top: 20px; margin-bottom: 5px;">
    Statistical Modelling Cheat Sheet
    <a href="/files/HS21_Statistical_Modelling_HS21_last.pdf" target="_blank" style="font-size: 0.7em; color: #0066cc; text-decoration: none; margin-left: 10px;">[pdf]</a>
  </h3>
  <details>
    <summary style="cursor: pointer; color: #0066cc; font-weight: bold; margin-bottom: 10px;">Click to view Table of Contents</summary>
    <div style="padding: 15px; background-color: #ffffff; border-radius: 5px; border: 1px solid #e0e0e0;">
      <h2>Table of Contents</h2>
      <ol style="padding-left: 20px;">
        <li>Classical Linear Model
          <ul>
            <li>Modelling Effect of Covariates</li>
            <li>Parameter Estimation</li>
            <li>Geometric Properties</li>
            <li>Analysis of Variance</li>
            <li>Statistical Properties</li>
            <li>Asymptotic Properties of LSE</li>
            <li>Statistical Properties of Residuals</li>
          </ul>
        </li>
        <li>Hypotheses Testing</li>
        <li>Multiple Testing</li>
        <li>Model Selection</li>
        <li>Model Diagnostic</li>
        <li>General Linear Model</li>
        <li>Robust Regression</li>
        <li>Generalized Linear Models</li>
        <li>Penalized Regression</li>
        <li>Maths Tricks Tutorials</li>
      </ol>
    </div>
  </details>


  <p style="margin-top: 15px; font-style: italic; color: #666;">
 Whether you're preparing for exams, conducting research, or aiming to deepen your understanding of statistical methods, these notes offer valuable insights and explanations to support your learning journey.