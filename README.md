# Covid-19 Bayesian Networks
This repo contains the codes for generating the Bayesian network structure and the conditional probability distributions (CPDs) of COVID-19 severity variables based on data collected from the CDC for 25 states in US. It serves the purpose of expanding the applicability of Bayesian networks and machine learning for post-detection analysis.

* Bayesian Net.ipynb -> This file contains the code for which the bayesian network and CPDs are generated from the COVID-19 dataset. To be able to read the CPDs, it is recommended that you download the file and/or open in a jupyter notebook.

* CPD_plots.ipynb -> It is used to plot the CPDs of some severity variables to interpretability.

* DSID_model.ipynb -> Contains code for designing the supervised ML model architecture (using Tensorflow and Keras framework) and plots the metrics for comparison.

## Citation
If you use this code in your work, please cite the accompanying paper:
```
@misc{ajayi2024bayesian,
      title={Bayesian Networks and Machine Learning for COVID-19 Severity Explanation and Demographic Symptom Classification}, 
      author={Oluwaseun T. Ajayi and Yu Cheng},
      year={2024},
      eprint={2406.10807},
      archivePrefix={arXiv},
      primaryClass={id='stat.ML' full_name='Machine Learning' is_active=True alt_name=None in_archive='stat' is_general=False description='Covers machine learning papers (supervised, unsupervised, semi-supervised learning, graphical models, reinforcement learning, bandits, high dimensional inference, etc.) with a statistical or theoretical grounding'}
}
```
