## Hi there👋, my name is Sabyasachi Ghosh.

## About Me

![Profile Views](https://komarev.com/ghpvc/?username=Sabyasachi-Data&color=blueviolet&style=flat)

I am a computational mechanics researcher and PhD candidate at the [Applied Mechanics](https://www.iiests.ac.in/IIEST/StudDetails/?id=MTYxNQ==) Department of IIEST Shibpur, India.  

My research interests include applying machine learning, neural networks and finite element methods (utilising ABAQUS, ANSYS, and FORTRAN) to structural dynamics ┬─┬.  

- 🔭 Currently SME @ Mercor
- 🌱 I’m currently upskilling in neural networks, SQL and Power BI 🚀
- 📄 All my latest publications are available [here](https://scholar.google.com/citations?hl=en&user=MDWJF_sAAAAJ&view_op=list_works&sortby=pubdate).

## 📦 Featured Projects

### 🔬 [Gaussian Process Machine Learning Surrogate Model](https://github.com/Sabyasachi-Data/Shell-GP-Machine-Learning-Surrogate-Model)

**A production-style Python framework that reduces expensive FEM computations with a probabilistic Gaussian Process surrogate for fast uncertainty quantification and variance-based (Sobol) global sensitivity analysis.**

Developed an end-to-end ML pipeline for composite shell frequency-response prediction with:

- **Gaussian Process Regression**: Zero-mean GP prior with Matérn covariance + white-noise term to capture residual modelling/meshing/measurement effects; scikit-learn–style modular components (custom transformers, swappable kernels)
- **Model performance**: Test RMSE = 14.122; R<sup>2</sup> = 0.981 (strong generalization on held-out data)
- **Uncertainty Quantification**: Posterior predictive mean + pointwise standard deviation, with optional 95% predictive intervals for risk-aware inference
- **Sobol Sensitivity Analysis**: Variance decomposition–based Sobol indices (first/total/second-order) using ~50,000 surrogate evaluations to rank dominant parameters
- **Visualizations**: Parity plots, residual analysis, sensitivity heatmaps, predicitions with uncertainty
- **Research Outcomes**: Demonstrated that Winkler/Pasternak foundation parameters, material orthotropy, and thickness ratio significantly influence the frequency response and quantified influence of individual parameters on model outcomes.
- **Publication**: Published in peer‑reviewed international journals (including Computers & Structures and the International Journal of Mechanics and Materials in Design)

**Tech Stack:** `Python` · `scikit-learn` · `Matplotlib` · `NumPy` · `Pandas` . `Seaborn`

<table border="0" cellspacing="0" cellpadding="0">
  <tr>
    <td align="center" width="42.5%">
      <img src="https://github.com/Sabyasachi-Data/Machine-Learning-Surrogate-Model_framework_for_shells/blob/main/outputs/figures/parity_plot.png"
           alt="Parity Plot" width="100%">
      <br>
      <sub><i>Predicted vs actual deflection values. Points close to the diagonal indicate accurate predictions. R² = 0.98, MAE = 5.747, RMSE = 10.39.</i></sub>
    </td>
    <td align="center" width="57.5%">
      <img src="https://github.com/Sabyasachi-Data/Machine-Learning-Surrogate-Model_framework_for_shells/blob/main/outputs/figures/predictions_uncertainty_2.png"
           alt="Predictions with Uncertainty" width="100%">
      <br>
      <sub><i>Low predictive S.D. in data-dense regions and higher S.D. where data are sparse. Gaussian process regression naturally provides calibrated output in predictive mean and variance terms, better suited than ordinary least squares for heteroscedastic frequency data.</i></sub>
    </td>
  </tr>
</table>


[![View on GitHub](https://img.shields.io/badge/View%20on-GitHub-181717?logo=github)](https://github.com/Sabyasachi-Data/Shell-GP-Machine-Learning-Surrogate-Model)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)

## I am currently seeking:

- 🎯 Exciting **pivotal industry ML/data science** roles in health-tech, finance or consulting fields
- ⚡ high-impact **postdoctoral** opportunities integrating AI with computational mechanics and structural engineering problems.  

## 👨🏻‍💻 I am skilled in: 

Python, PyTorch, Scikit-Learn, Data Analysis and Visualisation, Sensitivity Analysis, and Uncertainty Quantification.

## 📫 How to reach me: 

You can reach me on [eMail](mailto:sabyasachighos@gmail.com), [LinkedIn](https://www.linkedin.com/in/sabyasachi-ghosh-7098a7272/) or contact me on this page [here](https://sabyasachi-data.github.io/).

<!--
**Sabyasachi-Data/Sabyasachi-Data** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
