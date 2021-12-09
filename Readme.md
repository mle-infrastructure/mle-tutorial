# A Tutorial Repository for the MLE-Infrastructure 🔺
<a href="https://github.com/mle-infrastructure/mle-tutorial/blob/main/docs/logo_transparent.png?raw=true"><img src="https://github.com/mle-infrastructure/mle-tutorial/blob/main/docs/logo_transparent.png?raw=true" width="200" align="right" /></a>

This is a tutorial repository on how to get started with the MLE-Infrastructure:

- [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mle-infrastructure/mle-tutorial/blob/main/tutorial.ipynb)
- Example template project repository: [`mle-project`](https://github.com/mle-infrastructure/mle-project).

## Published Papers Using the `mle-toolbox`

Here is a set of published papers using the `mle-toolbox` to generate their results:

- [Vischer*, M. A., Lange*, R. T., & Sprekeler, H. (2021). On Lottery Tickets and Minimal Task Representations in Deep Reinforcement Learning. arXiv preprint arXiv:2105.01648.](https://arxiv.org/pdf/2105.01648.pdf)
- [Lange, R. T., & Sprekeler, H. (2020). Learning not to learn: Nature versus nurture in silico. Published as a conference paper at AAAI 2022.](https://arxiv.org/pdf/2010.04466.pdf)

## Additional Detailed Example Experiments

|              | Job Types|        Description                                                        |
| -------------------------- |-------------- | -------------------------------------------------------------- |
| 📄 **[Single-Objective](https://github.com/mle-infrastructure/mle-toolbox/tree/main/examples/toy_single_objective)** |  `multi-configs`, `hyperparameter-search`     | Core experiment types.              |
| 📄 **[Multi-Objective](https://github.com/mle-infrastructure/mle-toolbox/tree/main/examples/toy_multi_objective)**       | `hyperparameter-search`     | Multi-objective tuning. |
|  📄 **[Multi Bash](https://github.com/mle-infrastructure/mle-toolbox/tree/main/examples/bash_multi_config)**      | `multi-configs`     | Bash-based jobs.                        |
| 📄 **[Quadratic PBT](https://github.com/mle-infrastructure/mle-toolbox/tree/main/examples/pbt_quadratic)**            | `population-based-training`    | PBT on toy quadratic surrogate.                          |
| 📓 **[Evaluation](https://github.com/mle-infrastructure/mle-toolbox/tree/main/notebooks/evaluate_results.ipynb)**          | -     | Evaluation of gridsearch results. |
| 📓 **[GIF Animations](https://github.com/mle-infrastructure/mle-toolbox/tree/main/notebooks/animate_results.ipynb)** | -     | Walk through a set of animation helpers.      |
| 📓 **[Testing](https://github.com/mle-infrastructure/mle-toolbox/tree/main/notebooks/hypothesis_testing.ipynb)**     | -     | Perform hypothesis tests on logs.        |
|📓 **[PBT Evaluation](https://github.com/mle-infrastructure/mle-toolbox/tree/main/notebooks/inspect_pbt.ipynb)** | -     | Inspect the result from PBT.       

## ToDos

- [ ] Add LN2L, LTH DRL & criticality repositories after release.
- [ ] Add presentation slides and YouTube links later.
