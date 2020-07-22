# Data-Science-Project

This project includes the solution to the quant case studies. Each case question is solved in a separate Jupyter Notebook.

In order to ensure that the notebooks are reproducible, I have included a list of dependencies in the requirements.txt file.

To install these requirements for Python 3.7+, open Terminal on Mac or Command line in Windows and run

```
pip3 install -r requirements.txt
```

## Case Question 1: Language Classification

The solution for the language classification problem is found in the notebook **language_classification.ipynb**.

The code reads in a data file called **lang_data.csv** which is found in this directory.

The trained models are saved as pickle files (.pkl). In total there are 3 trained models based on the decision tree, random forest, and gradient boost.

These trained models can be loaded as decribed in the notebook and used to classify new data.

## Case Question 2: Pong


The solution for the pong - option B problem is found in the notebook **pong.ipynb**.

The trained reinforcement learning (RL) model is saved in a pickle file called **RL.pkl**.

The trained model can be loaded as described in the notebook.

**NB:** Running the notebook takes a long time.
