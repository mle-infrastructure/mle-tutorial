# A Tutorial Repository for the MLE-Infrastructure 🔺
<a href="https://github.com/mle-infrastructure/mle-tutorial/blob/main/docs/logo_transparent.png?raw=true"><img src="https://github.com/mle-infrastructure/mle-tutorial/blob/main/docs/logo_transparent.png?raw=true" width="150" align="right" /></a>

This is a tutorial repository on how to get started with the MLE-Infrastructure:

- Google Colab walkthrough: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mle-infrastructure/mle-tutorial/blob/main/tutorial.ipynb)
- Example template project repository: [`mle-project`](https://github.com/mle-infrastructure/mle-project).

## Individual Package Walkthroughs

1. **[`mle-logging`](https://github.com/mle-infrastructure/mle-logging)**: A Lightweight Logger for ML Experiments 📖 [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mle-infrastructure/mle-logging/blob/main/examples/getting_started.ipynb)
2. **[`mle-scheduler`](https://github.com/mle-infrastructure/mle-scheduler)**: A Lightweight Cluster/Cloud VM Job Management Tool 🚀 [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mle-infrastructure/mle-scheduler/blob/main/examples/getting_started.ipynb)
3. **[`mle-hyperopt`](https://github.com/mle-infrastructure/mle-hyperopt)**: A Lightweight Hyperparameter Optimization Tool 🚂 [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mle-infrastructure/mle-hyperopt/blob/main/examples/getting_started.ipynb)
4. **[`mle-monitor`](https://github.com/mle-infrastructure/mle-monitor)**: A Lightweight Experiment & Resource Monitoring Tool 📺 [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mle-infrastructure/mle-monitor/blob/main/examples/getting_started.ipynb)
5. **[`mle-toolbox`](https://github.com/mle-infrastructure/mle-toolbox)**: A Lightweight Tool to Manage Distributed ML Experiments 🛠 [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mle-infrastructure/mle-tutorial/blob/main/tutorial.ipynb)

## Published Papers Using the `mle-toolbox`

Here is a set of published papers using the `mle-toolbox` experiment infrastructure to generate their results:

- [Vischer*, M. A., Lange*, R. T., & Sprekeler, H. (2021). On Lottery Tickets and Minimal Task Representations in Deep Reinforcement Learning. arXiv preprint arXiv:2105.01648.](https://arxiv.org/pdf/2105.01648.pdf)
- [Lange, R. T., & Sprekeler, H. (2020). Learning not to learn: Nature versus nurture in silico. Published as a conference paper at AAAI 2022.](https://arxiv.org/pdf/2010.04466.pdf)

## Examples 📄 & Notebook Walkthroughs 📓

|              | Job Types|        Description                                                        |
| -------------------------- |-------------- | -------------------------------------------------------------- |
| 📄 **[Single-Objective](https://github.com/mle-infrastructure/mle-toolbox/tree/main/examples/toy_single_objective)** |  `multi-configs`, `hyperparameter-search`     | Core experiment types.              |
| 📄 **[Multi-Objective](https://github.com/mle-infrastructure/mle-toolbox/tree/main/examples/toy_multi_objective)**       | `hyperparameter-search`     | Multi-objective tuning. |
|  📄 **[Multi Bash](https://github.com/mle-infrastructure/mle-toolbox/tree/main/examples/bash_multi_config)**      | `multi-configs`     | Bash-based jobs.                        |
| 📄 **[Quadratic PBT](https://github.com/mle-infrastructure/mle-toolbox/tree/main/examples/pbt_quadratic)**            | `population-based-training`    | PBT on toy quadratic surrogate.                          |

|              | Description|        Colab                                                        |
| -------------------------- |-------------- | -------------------------------------------------------------- |
| 📓 **[Getting Started](https://github.com/mle-infrastructure/mle-toolbox/tree/main/notebooks/getting_started.ipynb)**          |  Get started with the toolbox. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mle-infrastructure/mle-toolbox/blob/main/notebooks/getting_started.ipynb)
| 📓 **[Subpackages](https://github.com/mle-infrastructure/mle-tutorial/tree/main/tutorial.ipynb)**          |  Get started with the toolbox subpackages. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mle-infrastructure/mle-toolbox/blob/main/notebooks/getting_started.ipynb)
| 📓 **[Evaluation](https://github.com/mle-infrastructure/mle-toolbox/tree/main/notebooks/evaluate_results.ipynb)**          |  Evaluation of gridsearch results. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mle-infrastructure/mle-toolbox/blob/main/notebooks/evaluate_results.ipynb)
| 📓 **[GIF Animations](https://github.com/mle-infrastructure/mle-toolbox/tree/main/notebooks/animate_results.ipynb)** |  Walk through a set of animation helpers.      | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mle-infrastructure/mle-toolbox/blob/main/notebooks/animate_results.ipynb)
| 📓 **[Testing](https://github.com/mle-infrastructure/mle-toolbox/tree/main/notebooks/hypothesis_testing.ipynb)**     | Perform hypothesis tests on logs.        | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mle-infrastructure/mle-toolbox/blob/main/notebooks/hypothesis_testing.ipynb)
|📓 **[PBT Evaluation](https://github.com/mle-infrastructure/mle-toolbox/tree/main/notebooks/inspect_pbt.ipynb)** | Inspect the result from PBT.   | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mle-infrastructure/mle-toolbox/blob/main/notebooks/inspect_pbt.ipynb)    

## ToDos

- [ ] Add LN2L, LTH DRL & criticality repositories after release.
- [ ] Add presentation slides and YouTube links later.
- [ ] Add blog post links using the toolbox?
