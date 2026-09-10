# Double-Debiased-ML

The purpose of this mini project is to review and to practice working with Double/Debiased Machine Learning (DML) for causal inference. <br>

For the application, I will work with 1) simple simulated data and 2) randomized clinical trials. <br>

My personal notes on related concepts and methods are available in [notes.md](https://github.com/minjee-kim/Double-Debiased-ML/blob/main/notes.md). <br>

### Overview

This repository is organized to begin with the basics of Double/Debiased Machine Learning and to gradually move toward applied causal inference examples.

The `analysis/` folder contains the main tutorials and analyses.

The `R/` folder contains reusable functions used throughout the project.

Simulation scripts, results, figures, and data are stored separately in their corresponding folders.

The analyses are organized as follows:

1.  **DML from scratch** — manually implement a basic Double/Debiased Machine Learningin a simple partially linear regression to understand what the algorithm does.

2.  **Cross-fitting and orthogonality** — examine the roles of sample splitting, cross-fitting, and orthogonality in DML by removing each piece from the algorithm and comparing the results.

3.  **Using the DoubleML package** — reproduce the basic DML workflow using the `DoubleML` package to learn how to use the package.

4.  **ATE estimation with the Interactive Regression Model (IRM)** — use DML to estimate the average treatment effect (binary treatment) with flexible nuisance-function estimation.

5.  **Randomized clinical trial simulation** — investigate how DML behaves in simulated randomized clinical trial settings.

6.  **Real randomized clinical trial application** — apply DML to data from a randomized clinical trial.

### Reference

The primary reference for this project is Chernozhukov et al. (2018), Double/Debiased Machine Learning for Treatment and Structural Parameters.

Additional Resources:

- [DoubleML documentation](https://docs.doubleml.org/stable/index.html)

- [An Introduction to Double/Debiased Machine Learning](https://arxiv.org/pdf/2504.08324) by Ahrens, Chernozhukov, Hansen, etc.

- [Applied Causal Inference Powered by ML and AI](https://causalml-book.org/chapters/CausalML_book_2022.pdf)
