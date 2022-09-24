To run script:

1. Install Python 3 along with Jupyter Notebook, Scikit-learn, scipy, pandas, and other relevant dependencies.
2. Open terminal and run Jupyter Notebook, then run the code.

Results.zip description:
1a: Experiments all classifiers with all preprocessing methods without variance threshold
1b: Experiments all classifiers with all preprocessing methods with variance threshold

Take the best classifier settings from 1a or 1b (based on preprocessing method and variance threshold),
2a: Experiment all classifiers on PCA feature selection method and intensity level.
2b: Experiment all classifiers on KBest(f-classif) feature selection method and intensity level.
2c: Experiment all classifiers on RF feature selection method and intensity level.

default-optimal, KBest_f_classif-optimal, PCA-optimal, RF-optimal contains all classifiers with the best results based on their feature selection method and intensity levels.

0: Displays all classifiers based on the best settings.
0!: Displays all classifiers based on the best settings with only internal metrics features.
0!! Displays all classifiers based on the best settings with only external metrics features.


Importance-Results-Raw: Displays all the raw permutation-importance results for each classifier with the best settings in 0.

Importance-FrequencyCount-PI: Displays aggregated unique features in all top 20 occuring features in permutation-importance results.

Importance-Category: Displays all software categories based on the aggregation of entrys in the Importance-FrequencyCount-PI where each software metric entry counts as 1. Each software metric entry is categorised based on Table 1 in the paper.


Internal Metrics descriptions and explanations can be found in SourceMeter-Metrics-Description.html.
